# GOGO 美西 · 从海风到巨杉

一个可直接部署到 GitHub Pages 的静态旅行网站。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个 repository，例如 `gogo-west-coast`。
2. 上传此文件夹中的全部文件，保持 `index.html` 在 repository 根目录。
3. 打开 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 选择 **Deploy from a branch**，branch 选 `main`，folder 选 `/(root)`，然后保存。
5. 等待 GitHub 发布完成后，在 Pages 页面打开网站链接。

## 自动更新

网站本身无需重新上传来更新天气。访问者每次打开页面时，页面会自动读取最近 16 天的沿途预报，并更新「出发清单」内的天气与打包提醒。

行程、酒店、景点等固定内容需要改动时，编辑 `index.html` 并重新上传即可。

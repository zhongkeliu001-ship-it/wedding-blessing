# 吾师有喜 · 婚礼祝福页

为老师李成龙与朱彩奕制作的学生祝福页面。页面为纯静态文件，样式和交互内嵌在 `index.html` 中。

## 正式页面

https://zhongkeliu001-ship-it.github.io/wedding-blessing/

由 GitHub Pages 从 `main` 分支根目录发布，使用 HTTPS。

## 二维码

- `qrcode.png`：酒红色美化版，1000 × 1000 px
- `qrcode_plain.png`：黑白备用版，1000 × 1000 px

两个二维码均使用最高纠错级别 H，并由 OpenCV 解码校验，内容与正式页面 URL 完全一致。页面结尾内嵌美化版，并提供黑白备用版下载。

## 本地预览

在本目录启动静态文件服务器：

```bash
python -m http.server 8000
```

然后打开 `http://localhost:8000/`。

## 文件与待补充内容

- `index.html`：页面、样式与交互
- `assets/`：婚礼照片、视频与页面二维码
- `.nojekyll`：让 GitHub Pages 直接发布静态文件

婚礼日期已更新为 2026 年 9 月 20 日，地点为邵阳玫瑰园；席设信息已移除。落款学生姓名仍保留待填写占位，可在 `index.html` 中修改。


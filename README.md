# 黄金矿工 · Gold Digger

一个无需安装依赖、无需后端的中文黄金矿工网页游戏。所有画面均由 Canvas 实时绘制，无外部字体、图片、追踪或运行时依赖。

## 在线试玩

- [直接试玩（第三方 Raw.Githack 预览）](https://raw.githack.com/xuyangyang-younger/gold-miner-web/main/index.html)
- GitHub Pages：仓库 Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。部署成功后访问 https://xuyangyang-younger.github.io/gold-miner-web/ 。此地址仅在启用 Pages 并部署成功后可用。

## 玩法

- 点击矿区、点击“出钩”、空格或 ↓：出钩。
- X 或“炸药”：放弃正在拉回的矿物，加快回收。每局 2 份，每次过关补充 1 份。
- P / Esc 或“暂停”：暂停/继续。切换标签页会自动暂停。
- 每关 60 秒，收益达标后进入下一关，累计收益保留，目标逐步增加。
- 小 / 中 / 大金块分别 $100 / $250 / $500；钻石 $800；石头 $30；福袋 $100–600。
- 最高收益保存在当前浏览器 localStorage。音效默认关闭，可自行开启。

## 本地运行

直接用浏览器打开 `index.html`，或在项目目录运行：

```sh
python3 -m http.server 8000
```

再访问 http://localhost:8000 。适配电脑和手机，支持系统深浅色界面。

## 技术

原生 HTML、CSS、JavaScript、Canvas 2D、Web Audio。没有构建步骤。

## 许可

MIT，见 LICENSE。

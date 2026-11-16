# Kindle Chess

Kindle 第八代（600×800、16 级灰阶）内置浏览器可运行的单文件国际象棋。

- 在线版：https://yelina123.github.io/Kindle-chess/
- 离线版：下载 `kindle-chess.html`，放入 Kindle 的 `documents` 目录，用内置浏览器打开 `file:///mnt/us/documents/kindle-chess.html`

## 功能

- 完整规则：王车易位、吃过路兵、升变、将杀、逼和、五十回合、三次重复、子力不足
- 全点按操作（该浏览器只有 click 事件，没有 touch）
- 棋钟、暂停、加时、超时判负
- 棋盘编辑器、FEN 载入
- 2–3 层浅层分析与胜率条、人机对弈
- 纯黑白高对比，离线运行

- 自适应视口：按可用宽高等比缩放，手机、平板、Kindle 不横向滚动

## 兼容

针对 Kindle 第八代内置浏览器（WebKit 531.2–534.26 / Safari 4 时代）编写：ES3/ES5、无 flex/grid/calc、无 touch 事件、无 position:fixed。

## 分析引擎

内置 KindleChess Engine v1：Negamax + Alpha-Beta + 吃子静态搜索；评估为子力 + PST + 兵形 + 象对，非神经网络。分析面板显示胜率条，按引擎评分换算。

## 作者

[yelina123](https://github.com/yelina123)

## 棋子素材

Cburnett chess pieces from lichess lila，CC BY-SA 3.0。

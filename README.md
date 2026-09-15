# inner-mongolia-trip
2026 内蒙古国庆旅行攻略

手机旅行手册：每日行程、路线地图、预订状态、交通总览和行李清单。

GitHub Pages 启用并成功发布后，访问：
https://yolandayinyyy-lgtm.github.io/inner-mongolia-trip/

## 发布

在仓库 Settings → Pages → Build and deployment 中，将 Source 设为 GitHub Actions。
每次向 main 分支提交代码，工作流会检查、构建并发布网页；也可在 Actions 手动运行 Deploy travel guide。

## 本地开发

```sh
pnpm install
pnpm dev
pnpm build
```

行程数据：`src/data/itinerary.ts`。详细说明见 [DEVELOPMENT.md](DEVELOPMENT.md)。
预订状态和行李勾选仅保存在各自浏览器，不会同步给其他朋友。

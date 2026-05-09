# 熙映云软官网静态门户

纯静态企业官网，适用于 GitHub Pages 部署。

## 文件结构

- `index.html`：首页结构与 SEO 信息
- `styles.css`：视觉样式、响应式布局与动画
- `script.js`：导航交互、滚动显现与数字动画
- `CNAME`：自定义域名 `xyingsoft.com`
- `.nojekyll`：禁用 Jekyll，按纯静态资源发布

## 部署说明

1. 推送到 GitHub 仓库默认分支 `main`
2. 在仓库 `Settings -> Pages` 中确认使用 `Deploy from a branch`
3. 选择分支 `main`，目录 `/ (root)`
4. 域名 DNS 指向 GitHub Pages

## Apex 域名 `xyingsoft.com` 常用记录

- `A 185.199.108.153`
- `A 185.199.109.153`
- `A 185.199.110.153`
- `A 185.199.111.153`

可选 IPv6:

- `AAAA 2606:50c0:8000::153`
- `AAAA 2606:50c0:8001::153`
- `AAAA 2606:50c0:8002::153`
- `AAAA 2606:50c0:8003::153`

建议同时配置:

- `CNAME www -> <github-pages-default-domain>`

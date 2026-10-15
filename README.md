# shaoye.cc.cd

少爷的个人主页，托管在 GitHub Pages。

- 线上地址：https://shaoye.cc.cd
- 仓库：https://github.com/xiaoshuaidababa/xiaoshuaidababa.github.io

## ⚠️ 改动须知（先读）

1. **不要删除根目录 `CNAME` 文件**（内容 `shaoye.cc.cd`），删了自定义域名就掉了。
2. **不要把 `shaoye.cc.cd`（apex / `@`）改成 CNAME** —— 会冲掉 MX 记录，邮件转发立刻断。
3. 邮件链路：ImprovMX 转发（MX `mx1/mx2.improvmx.com`），SPF `include:spf.improvmx.com`。
   动 A 记录前务必确认 MX / SPF 还在。
4. 本仓库是纯静态站点，**不要引入必须付费的 CDN / 分析 / 建站 SaaS**。

## 文件说明

| 文件 | 用途 |
|---|---|
| `index.html` | 首页（单页） |
| `404.html` | 自定义 404 页 |
| `assets/style.css` | 样式（含深色模式） |
| `favicon.svg` / `favicon.ico` / `apple-touch-icon.png` | 站点图标 |
| `og-image.png` | 社交分享预览图（1200×630） |
| `robots.txt` / `sitemap.xml` | 搜索引擎抓取 |
| `CNAME` | GitHub Pages 自定义域名（**勿动**） |
| `.nojekyll` | 跳过 Jekyll 处理，按原样发布 |

## 怎么改内容

直接编辑 `index.html`：简介在「关于我」，链接在「链接」区块，联系方式在「联系」区块。
改完提交到 `main` 分支，GitHub Pages 会在 1 分钟内自动重新发布。

## 部署

```bash
git clone git@github.com:xiaoshuaidababa/xiaoshuaidababa.github.io.git
# 修改文件后
git add -A && git commit -m "update site" && git push origin main
```

## 相关文档

- 改进清单（审计结果与待办）：`shaoye.cc.cd-improvements.md`
- 权威交接与后台入口：`shaoye.cc.cd.md`

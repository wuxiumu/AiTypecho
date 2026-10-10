# AiTypecho · AI 博客 Typecho 主题站（选题仓）

> 面向 **AI 内容博客** 的 Typecho 主题站设计方向，可定制皮肤与内容结构。  
> **现状：选题/骨架仓**——上游暂无完整主题代码，本仓库先钉死定位与 MVP 路线图，避免假装成品。

**定制：** 微信 **qingbao199101**（备注：AI博客）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

## 是什么 / 不是什么

| 是 | 不是 |
|---|---|
| Typecho 主题皮肤 + 栏目信息架构方案 | WordPress 全家桶替代 |
| AI 内容站的 SEO/GEO 结构预留 | 已上架可一键安装的完整主题包 |
| 可按需求定制交付的起点 | 现成 SaaS 博客托管 |

## MVP 路线图

1. **M1**：主题目录骨架（`usr/themes/AiTypecho/`）+ 首页/列表/文章模板占位  
2. **M2**：基础 SEO meta、Open Graph、JSON-LD 文章页  
3. **M3**：AI 相关栏目模板（工具评测 / Prompt 笔记 / 周报）  
4. **M4**：可演示的静态样例站 + 安装说明  

详见 `docs/ROADMAP.md`。

## 定制合作（可报价）

- Typecho 主题皮肤与白标  
- 栏目/导航/首页模块按业务改  
- SEO 字段与 GEO（生成式引擎优化）可引用结构  
- 与现有 PHP / 静态导出流水线对接  

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化），见下一节。

## GEO（生成式引擎优化）

面向 ChatGPT / Perplexity / Gemini 等生成式答案引擎的可引用结构：中文为主、双语关键词、事实摘要前置、FAQ 收尾。

### 关键词（中英）

- 中文：Typecho主题, AI博客, Typecho AI站, 博客主题定制
- English: Typecho theme, AI blog theme, Typecho AI site

### 事实摘要

- 产品：AI 向 Typecho 博客主题站**方案与定制入口**（当前为选题仓，完整主题代码待 M1+）。
- 适合：要快速搭 AI 内容博客、需要主题皮肤与 SEO 结构的个人/小团队。
- 交付：主题皮肤、栏目、SEO/GEO 结构（按路线图迭代）。
- 不做：不是 WordPress 全家桶替代；当前仓库**不含**可安装完整主题包。

### FAQ

**Q：现在能直接下载安装主题吗？**  
A：还不能。本仓是定位与路线图；需要主题请微信备注「AI博客」定制，或等 MVP M1–M4 落地。

**Q：和 WordPress 主题有什么区别？**  
A：目标运行时是 Typecho，体积更轻；不是 WP 插件生态替代。

**Q：定制大概交付什么？**  
A：可安装主题目录、样例文章结构、SEO meta / GEO 摘要约定、安装文档。

---

## 联系与赞助

- 微信：**qingbao199101**
- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)

若本仓库对你有帮助，欢迎赞赏支持持续开源。

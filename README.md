# ID Design Reference Archive — Privacy Policy

用于 Pinterest Developer App 的最简公开隐私政策页面。纯 HTML/CSS，无 JavaScript、依赖、表单或统计脚本。

## 文件

- `index.html`：英文隐私政策及响应式样式。
- `.nojekyll`：让 GitHub Pages 直接发布静态文件。

## 发布前

将 `index.html` 中的 `YOUR_EMAIL@example.com` 替换为可接收隐私问题的真实邮箱。核对页面描述与应用实际行为一致；页面本身不会实现数据访问限制或删除功能。后续修改政策时更新日期。

## 部署到 GitHub Pages

1. 在 GitHub 创建新的 **Public** 仓库，名称为 `id-design-reference-archive`。
2. 将本目录文件上传至仓库的 `main` 分支根目录，确保 `index.html` 不在额外的子目录里。也可用 Git 推送本地仓库。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment → Source** 选择 **Deploy from a branch**。
5. 在 **Branch** 选择 **main**，目录选择 **/(root)**，点击 **Save**。
6. 等待部署完成，在 Pages 设置里点击 **Visit site**。若暂时无法打开，可在仓库 **Actions** 查看 `pages build and deployment` 的状态。
7. 确认网页无需登录即可访问，再将完整 HTTPS 地址填入 Pinterest Developer App 的隐私政策链接字段。

发布地址格式：`https://<GitHub用户名>.github.io/id-design-reference-archive/`。

本项目已创建公开仓库并启用 Pages（`main` / 根目录）：

- 仓库：https://github.com/z790977870-bot/id-design-reference-archive
- 网站：https://z790977870-bot.github.io/id-design-reference-archive/
- Pages 设置：https://github.com/z790977870-bot/id-design-reference-archive/settings/pages

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 本地预览

直接用浏览器打开 `index.html` 即可。页面不需要构建步骤。

## 更新

修改 `index.html` 并提交到 `main`。配置好 Pages 后会自动重新发布。此页面用于披露应用的数据处理方式，不代表 Pinterest 已批准应用或其数据使用方式。

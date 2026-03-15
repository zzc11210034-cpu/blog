# 博客部署指南

## 📦 项目信息

- **项目名称**: 凡尘的自留地
- **文件位置**: `workspace/blog/index.html`
- **类型**: 单页静态博客
- **大小**: ~35KB

---

## 🚀 部署方案

### 方案一：Cloudflare Pages（推荐）⭐

**优点**:
- ✅ 免费永久
- ✅ 全球 CDN，速度快
- ✅ 自动 HTTPS
- ✅ 支持自定义域名
- ✅ 每月 10 万次请求（个人使用绰绰有余）

**部署步骤**:

#### 1. 准备 GitHub 仓库
```bash
# 如果你有 GitHub 账号：
1. 登录 GitHub
2. 创建新仓库，如 `blog`
3. 上传 `index.html` 文件
4. 确保文件在根目录
```

#### 2. 部署到 Cloudflare Pages
```
1. 访问 https://pages.cloudflare.com/
2. 登录 Cloudflare 账号（没有就注册一个，免费）
3. 点击 "Create a project"
4. 选择 "Connect to Git"
5. 选择你的 `blog` 仓库
6. 点击 "Begin setup"
7. 项目名：`fanchen-blog`（可自定义）
8. Production branch: `main`
9. 点击 "Save and Deploy"
10. 等待 1-2 分钟部署完成
```

**获得域名**: `fanchen-blog.pages.dev`

---

### 方案二：Vercel

**优点**: 部署简单，自动 SSL

**步骤**:
```
1. 访问 https://vercel.com/
2. 登录 GitHub 账号
3. 点击 "Add New Project"
4. 导入 `blog` 仓库
5. 点击 "Deploy"
```

**获得域名**: `fanchen-blog.vercel.app`

---

### 方案三：Netlify（最快）

**优点**: 拖拽部署，无需 Git

**步骤**:
```
1. 访问 https://app.netlify.com/drop
2. 把 `blog` 文件夹拖进去
3. 立即获得链接
```

**缺点**: 链接随机，不适合长期使用

---

## 🎯 推荐流程（5 分钟搞定）

### 如果你有 GitHub 账号：
1. 创建仓库并上传 `index.html`（2 分钟）
2. Cloudflare Pages 部署（2 分钟）
3. 测试访问（1 分钟）

### 如果你没有 GitHub 账号：
1. 注册 GitHub（3 分钟）
2. 创建仓库并上传（2 分钟）
3. Cloudflare Pages 部署（2 分钟）

---

## 📝 需要的信息

**请提供以下任一信息：**

### 选项 A：你有 GitHub 账号
- GitHub 用户名：________
- 我可以帮你创建仓库并上传代码

### 选项 B：你有 Cloudflare 账号
- Cloudflare 邮箱：________
- 我可以指导你手动部署

### 选项 C：都没有
- 我可以先用 Netlify Drop 生成临时链接
- 然后你再注册账号部署到永久平台

---

## 🔧 自动部署脚本（可选）

如果你有 GitHub 账号，我可以：
1. 创建 `deploy.ps1` 脚本
2. 一键上传到 GitHub
3. 自动触发 Cloudflare 部署

---

## 📊 部署后功能

- ✅ 全球访问
- ✅ HTTPS 加密
- ✅ 暗黑模式已内置
- ✅ 移动端优化
- ✅ SEO 友好
- ✅ 加载速度快（<1s）

---

## 💡 后续优化

- [ ] 添加评论功能（Giscus/Utterances）
- [ ] 添加 RSS Feed
- [ ] 添加文章搜索
- [ ] 添加阅读统计
- [ ] 自定义域名绑定

---

**准备就绪！告诉我你的选择，我马上开始部署！** 🚀

# 李雪涛 · 个人学术主页

多模态大模型 · 具身智能 · VLA 机器人算法方向的个人主页。

## 本地预览

直接双击 `index.html` 即可在浏览器打开。

## 部署方式（任选其一）

### 方式 A：GitHub Pages（推荐，免费且稳定）

1. 在 https://github.com/new 新建一个**公开**仓库，例如命名为 `homepage`。
2. 在本文件夹执行（把 `<你的用户名>` 换成你的 GitHub 用户名）：

   ```bash
   git remote add origin https://github.com/<你的用户名>/homepage.git
   git branch -M main
   git push -u origin main
   ```

3. 打开仓库 `Settings` → `Pages` → `Source` 选 `Deploy from a branch`，
   分支选 `main` / 目录 `/ (root)`，保存。
4. 约 1 分钟后，网址为：`https://<你的用户名>.github.io/homepage/`

如果想用更短的 `https://<你的用户名>.github.io/`，把仓库名命名为 `<你的用户名>.github.io` 即可。

### 方式 B：Netlify Drop（最快，零命令）

打开 https://app.netlify.com/drop ，把本文件夹（或 `index.html`）直接拖进去，
几秒后即可得到一个公开网址（可在站点设置里改成自定义名字）。

### 方式 C：Vercel

```bash
npm i -g vercel
vercel
```

按提示登录并确认，即可获得公开网址。

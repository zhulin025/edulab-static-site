# EduLab Static Site

这是一个纯静态课件站，课件 HTML 由 `@wy51ai/edulab@0.1.8` 预生成。

## 内容

- `index.html`：课件目录、搜索、分类筛选、内嵌预览。
- `lessons/solid/`：立体几何课件。
- `lessons/analytic/`：解析几何/圆锥曲线课件。
- `lessons/chem/`：化学反应课件。
- `vendor/edulab/`：上游 Apache-2.0 license 和 notice。

## 本地预览

直接打开：

```text
index.html
```

或用任意静态服务器：

```bash
python3 -m http.server 8080
```

## 部署

把整个 `edulab-static-site/` 目录作为静态站根目录上传即可。

当前线上地址：

- https://edulab-static-site.vercel.app
- https://edu.liuwa.xyz

Cloudflare Pages 推荐配置：

```text
Build command: 留空
Build output directory: edulab-static-site
```

如果把该目录单独作为一个仓库，输出目录可设为：

```text
.
```

## 来源与许可

课件生成自 `wy51ai/edulab`，上游许可证为 Apache-2.0。

保留文件：

- `vendor/edulab/LICENSE`
- `vendor/edulab/NOTICE`

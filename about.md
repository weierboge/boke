---
layout: default
title: 关于我
---

<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background: #fff;
            color: #333;
            min-height: 100vh; /* 确保至少为视窗高度 */
            display: flex;
            flex-direction: column; /* 页面内容为一列 */
        }
        header {
            background: #fff;
            border-bottom: 1px solid #eee;
            padding: 10px 0;
        }
        header h1 {
            text-align: center;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: #333;
            padding: 0 15px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            margin: 200px auto;
            max-width: 1200px;
            flex: 1; /* 占据除页头和页脚外的剩余空间 */
        }
        .main-content {
            flex: 1 0 60%; /* 占据主要空间，但至少60% */
            padding: 0 15px;
        }
        .sidebar {
            flex: 0 1 30%; /* 占据次要空间，但至少30% */
            padding: 0 15px;
            box-sizing: border-box;
        }
        .archive-list {
            list-style: none;
            padding: 0;
            font-size: 0.9em;
        }
        .archive-list li {
            margin-bottom: 5px;
        }
        .archive-year {
            font-weight: bold;
        }
         .social-icons a {
            margin: 0 50px;
            text-align: center;
            color: #0000CC; /* 图标颜色 */
            font-size: 24px; /* 增加图标大小 */
             border-top: 1px solid #eee;
        }
        .social-icons a:hover {
            color: ADD8E6; /* 鼠标悬停时图标颜色 */
        }
        .article-title {
            text-align: center;
            margin-bottom: 20px;
        }
        .article-meta {
            text-align: center;
            color: #666;
            margin-bottom: 20px;
        }
        .article-content {
            margin-bottom: 40px;
        }
        .article-content h2 {
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
            margin-top: 40px;
        }
        .article-content h3 {
            margin-top: 30px;
        }
        .article-content p {
            margin-bottom: 20px;
        }
        .article-content img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px 0;
        }
        .article-content blockquote {
            border-left: 4px solid #eee;
            padding-left: 20px;
            margin: 20px 0;
            color: #666;
        }
        .article-content ul,
        .article-content ol {
            margin: 20px 0;
            padding-left: 40px;
        }
        .article-content code {
            background: #f8f8f8;
            padding: 2px 6px;
            border-radius: 4px;
        }
        .article-content pre {
            background: #f8f8f8;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        .footer {
            background: #f8f8f8; 
            border-top: 1px solid #eee;
            text-align: center;
            padding: 20px 0;
            flex-shrink: 0;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="{{ '/' | relative_url }}">主页</a>
            <a href="{{ '/archive.html' | relative_url }}">归档</a>
        </nav>
    </header>
    <main>
        <p>我是韦二伯格，一名短视频从业者和编导专业人士，喜欢探索最新的科技数码产品和各种新鲜事物。
            我的其他工作内容 : 知乎数码博主、短视频运营一对一咨询、抖音快手视频号小红书等平台的短视频代运营、短视频策划、视频拍摄制作、知乎数码类商业写作等，在过去，我的优质内容量超过了400篇，吸引了1500万人次的浏览。
            如果您对我的创作感兴趣，欢迎通过我的主页签名上的方式联系我，进行合作。
</p>
        <div class="social-icons">
            <a href="https://www.zhihu.com/people/wei-shi-bo" target="_blank"><i class="fab fa-zhihu"></i></a>
            <!-- 添加其他社交链接 -->
            <a href="https://twitter.com/yourusername" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i></a>
            <!-- 更多图标 -->
        </div>
    </main>
    <footer class="footer">
        <p>&copy; 2024 韦二伯格 · 版权所有</p>
    </footer>
</body>
</html>
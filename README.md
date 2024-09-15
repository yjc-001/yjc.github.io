<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<title>个人简介</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: url('图库/6.gif') no-repeat center center fixed; /* 添加背景图片，实现全屏覆盖 */
    background-size: cover; /* 设置背景图片大小，使其覆盖整个屏幕 */
  }
  .container {
    width: 80%;
    margin: auto;
    overflow: hidden;
  }
  header {
    background: #3e4d57;
    color: #ffffff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #8284e0 3px solid; /* 设置页眉背景颜色、文字颜色、内边距、最小高度和底部边框 */
  }
  header a {
    color: #ffffff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
  }
  header ul {
    padding: 0;
    list-style: none;
  }
  header li {
    float: left;
    display: inline;
    padding: 0 20px 0 20px;
    transition: transform 0.3s;
  }
  header li:hover {
  transform: scale(1.1); 
}
  header #branding {
    float: left;
  }
  header #branding h1 {
    margin: 0;
  }
  header nav {
    float: right;
    margin-top: 10px;
  }
  header .highlight, header .current a {
    color: #8567f1;
    font-weight: bold;
  }
  header a:hover {
    color: #ffffff;
    font-weight: bold;
  }
  .profile img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin-bottom: 20px;
    transition: transform 0.3s;
  }
  .profile img:hover {
    transform: scale(1.1);
  }
  .profile h2 {
    margin: 0 0 10px 0;
    color: #ffffff;
    margin-top: 170px;
  }
  .profile p {
    margin-bottom: 20px;
    color: #ffffff;
  }
  .avatar-container {
  position: absolute;
  top: 46%;
  left: 82%;
  transform: translate(-50%, -50%);
  }
  .small-font {
  font-size: 0.6em; 
  }

</style>
</head>
<body>

<header>
  <div class="container">
    <div id="branding">
      <h1><span class="highlight">风亐</span>的个人简介</h1>
    </div>
    <nav>
      <ul>
        <li class="current"><a href="#profile">风亐<span class="small-font">（简介）</span></a></li>
        <li><a href="https://yjc-001.github.io/.github.io/yinyue.html">风悦<span class="small-font">（音乐播放器）</span></a></li>
        <li><a [href="https://yjc-001.github.io/.github.io/风阅.html](https://yjc-001.github.io/.github.io/%E9%A3%8E%E9%98%85.html)">风阅<span class="small-font">（网页模板）</span></a></li>
      </ul>
    </nav>
  </div>
</header>
<section class="profile" id="profile">
  <div class="avatar-container">
    <img src="图库/1.jpg" alt="风亐的照片">
  </div>
  <div class="container">
    <h2>风亐</h2>
    <p>我是一名热衷于编程和软件开发的自由工作者，拥有多年的项目经验。</p>
    <p>我是一个出生于2000年5月10号的男生，热爱计算机和人工智能相关的领域。我喜欢蓝色，它给我一种宁静和平和的感觉。在我的业余时间，我喜欢爬山和旅游，这让我能够放松身心，同时也能欣赏大自然的美景。

      我对电脑相关的内容非常感兴趣，并且有一些相关的技能。我熟悉Python编程语言，能够使用简单的爬虫技术来获取网页数据。此外，我还能制作一些小游戏，并具备一定的Web前端开发能力。我还熟悉使用Photoshop和Premiere等软件，可以进行简单的图像和视频编辑。

      我对人工智能领域也有浓厚的兴趣，我希望能够深入学习和研究这个领域的技术和应用。我相信通过不断学习和实践，我能够在计算机行业中取得更多的成就。

      以上是我的简介，希望能够与您进一步交流和合作。如果您有任何问题或需要进一步了解，请随时告诉我。</p>
    <p>技能：</p>
    <p>技能1：Python爬虫：我熟悉Python编程语言，并能够使用它进行简单的爬虫开发。我可以编写脚本来自动获取网页数据，进行数据分析和处理。</p>
    <p>技能2：小游戏制作：我有一定的小游戏制作经验。我可以使用合适的游戏引擎和编程语言来设计和开发简单的游戏，为用户带来娱乐和乐趣。</p>
    <p>技能3：Web前端开发：我熟悉Web前端开发，能够使用HTML、CSS和JavaScript等技术来构建用户友好的网页界面。我可以创建响应式的网站，并实现一些交互功能，提升用户体验。</p>
    <p>技能4：平面设计：我熟练使用Photoshop和其他平面设计工具，可以进行商品详情页的设计和制作。我能够根据电商的需求，设计出吸引人的商品展示页面，提升用户的购物体验。</p>
    <p>联系方式：
      <br>我的邮箱:2029479643@qq.com
      <br>我的电话:18798755738
    </p>
    </div>
</section>

</body>
</html>

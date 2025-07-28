# yealqp的个人主页

一个现代化的个人主页网站，展示个人信息、项目作品和技能。

## 🌟 特性

- **响应式设计** - 完美适配桌面端和移动端
- **现代化UI** - 简洁美观的界面设计
- **动画效果** - 流畅的页面加载和交互动画
- **项目展示** - 展示个人项目和作品
- **技能可视化** - SVG技能图表展示
- **社交链接** - 多平台社交媒体链接
- **时间线** - 个人发展历程展示

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **字体**: Ubuntu, Pacifico
- **图标**: SVG矢量图标
- **动画**: CSS3 Transitions & Animations
- **响应式**: CSS Media Queries

## 📁 项目结构

```
YealqpWebsite/
├── index.html              # 主页面
├── favicon.ico             # 网站图标
├── README.md              # 项目说明
└── static/                # 静态资源目录
    ├── css/               # 样式文件
    │   ├── root.css       # CSS变量定义
    │   └── style.css      # 主样式文件
    ├── js/                # JavaScript文件
    │   └── script.js      # 主脚本文件
    ├── fonts/             # 字体文件
    │   ├── Pacifico-Regular.ttf
    │   └── Ubuntu-Regular.ttf
    ├── img/               # 图片资源
    │   ├── logo.png       # 头像
    │   ├── logokuang.png  # 头像装饰框
    │   ├── background.jpg # 背景图片
    │   └── ...           # 其他图片
    └── svg/               # SVG文件
        ├── skillPc.svg    # 桌面端技能图
        ├── skillWap.svg   # 移动端技能图
        └── snake-*.svg    # 贪吃蛇游戏图标
```

## 🎨 主要功能

### 左侧边栏
- **个人头像** - 带装饰框的头像展示
- **基本信息** - 地理位置、工作信息
- **标签云** - 个人技能和兴趣标签
- **时间线** - 个人发展历程时间轴

### 右侧主内容
- **欢迎区域** - 个人介绍和职业描述
- **社交链接** - GitHub、邮箱、QQ等联系方式
- **项目展示** - 个人网站项目列表
- **技能展示** - SVG技能图表
- **贪吃蛇游戏** - 互动小游戏

### 交互功能
- **项目卡片点击效果** - 鼠标按下/释放动画
- **图片弹窗** - 点击查看大图功能
- **响应式布局** - 移动端自适应
- **页面加载动画** - 优雅的加载过渡效果

## 🚀 快速开始

### 本地运行

1. 克隆项目到本地
```bash
git clone https://github.com/yealqp/YealqpWebsite.git
cd YealqpWebsite
```

2. 使用本地服务器运行

使用任意Web服务器运行
### 部署

项目为纯静态网站，可以部署到任何静态网站托管服务：

- **GitHub Pages**
- **Vercel**
- **Netlify**

## ⚙️ 自定义配置

### 修改个人信息

1. **基本信息**: 编辑 `index.html` 中的个人信息部分
2. **头像**: 替换 `static/img/logo.png`
3. **背景**: 替换 `static/img/background.jpg`
4. **项目链接**: 修改项目展示区域的链接和描述
5. **社交链接**: 更新社交媒体链接地址

### 样式自定义

- **主题色彩**: 修改 `static/css/root.css` 中的CSS变量
- **布局调整**: 编辑 `static/css/style.css`
- **响应式断点**: 调整媒体查询设置

### 功能扩展

- **添加新项目**: 在项目展示区域添加新的项目卡片
- **技能更新**: 替换或修改 `static/svg/skill*.svg` 文件
- **时间线更新**: 在左侧时间线中添加新的里程碑

## 📱 响应式设计

- **桌面端** (>800px): 左右分栏布局
- **移动端** (≤800px): 单栏布局，左侧边栏隐藏
- **平板端**: 自适应布局调整

## 🎯 性能优化

- **字体优化**: 使用 `font-display: swap` 提升加载性能
- **图片优化**: SVG矢量图标，减少文件大小
- **CSS优化**: 合理的选择器和动画性能
- **JavaScript优化**: 事件委托和性能友好的交互

## 📄 许可证

该项目二开自Zyyo的[开源html个人主页](https://github.com/ZYYO666/homepage)，源项目未说明许可证，请自行评估。
## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## 📞 联系方式

- **邮箱**: yealqp@163.com
- **GitHub**: [yealqp](https://github.com/yealqp/)

---

⭐ 如果这个项目对你有帮助，请给它一个星标！
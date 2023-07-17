# 草原的博客

> 欢迎来到草原的博客！这里是一个关于科技、创新和未来的社区。草原的博客致力于探讨各种各样的主题，包括加密货币、人工智能、机器学习、区块链、虚拟现实和物联网等。

## 关于页面

关于页面的内容在 `source/about/index.md` 文件中，你可以修改其中的内容。

## 新增文章

> 这里保存之后就会发布到网站，所以建议在 mdnice 写好之后再上传。

1. 在`source/_posts`目录下新建一个`markdown`文件，文件名格式为`英文标题.md`，例如`hello-world.md`。
2. 在`markdown`文件头部添加如下内容：

```md
---
title: 标题
date: 发布时间（格式：2023-07-17 20:00:00）
tags:
  - 标签1
  - 标签2
categories:
  - 类别
description: 描述
cover: 封面图片（可选）
---
```

## 新增友链

参考 `source/_data/link.yml` 文件，按照格式新增友链即可。

## 站点信息修改

如果你对默认生成的站点信息不满意，可以在 `config.yml` 文件中修改：

```yml
title: 草原的博客
subtitle: 探索技术、科学和文化的无限可能性
description: 欢迎来到草原的博客！这里是一个关于科技、创新和未来的社区。草原的博客致力于探讨各种各样的主题，包括加密货币、人工智能、机器学习、区块链、虚拟现实和物联网等。
keywords:
  - 加密货币
  - 人工智能
  - 机器学习
  - 区块链
  - 虚拟现实
  - 物联网
# 作者名称，会显示在侧边栏
author: CY
```

左侧作者信息栏的描述可以在 `_config.butterfly.yml` 文件中修改：

```yml
card_author:
  description: 探索技术、科学和文化的无限可能性
```

公告也可以在 `_config.butterfly.yml` 文件中修改：

```yml
card_announcement:
  content: A simple and elegant blog
```

## 更换图片

默认的头图和封面图可能不适合你，这些都在 `_config.butterfly.yml` 文件中：

```yml
# 首页 banner 图片
index_img: https://cdn.jsdelivr.net/gh/youngjuning/images@main/1689604945346.png

# 页面默认头图
default_top_img: https://s2.loli.net/2023/07/17/leDBhzw8xEnOmS6.png

# 归档页面默认头图
archive_img: https://s2.loli.net/2023/07/17/xoflNAZpqPTFKU9.png

# 标签页默认头图
tag_img: https://s2.loli.net/2023/07/17/wvkgLUtdju3hYqr.png

# 分类页默认头图
category_img: https://s2.loli.net/2023/07/17/i8TsAaOQYEj1kIv.png

cover:
  # 文章页默认封面（随机）
  default_cover:
    - https://s2.loli.net/2023/07/17/9JQuLefqURI7DYi.png
    - https://s2.loli.net/2023/07/17/qkCs3dgYblAB7ar.png
    - https://s2.loli.net/2023/07/17/XvsoykKqNSQbBUj.png
    - https://s2.loli.net/2023/07/17/mnMagitJQlyNfHk.png
    - https://s2.loli.net/2023/07/17/UShtHMTzDNAblBV.png
    - https://s2.loli.net/2023/07/17/sHCFR6fanbPMwpD.png
    - https://s2.loli.net/2023/07/17/tjNbDh17cTQiJMB.png
    - https://s2.loli.net/2023/07/17/eS6iXfpscLyUhVC.png
```
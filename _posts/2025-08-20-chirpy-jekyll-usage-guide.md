---
title: Chirpy Jekyll 使用指北
date: 2025-08-20 21:40:00 +0800
categories:
  - Jekyll chirpy
tags:
  - Jekyll_chirpy
---
[jekyll-theme-chirpy Wiki](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)

---

#### 文件名与文章标题的区别

- **例子**：
    
    - 文件名：`2025-08-20-chirpy-jekyll-usage-guide.md`
        
    - 文章标题：`Chirpy Jekyll 使用指南`
        
- **要点**：文件名和文章标题不用完全相同。
    
- **原因**：文件名服务于系统和 URL，标题服务于读者。两者职能不同。
    
- **最佳做法**：
    
    1. **文件名（机器友好）**：**全部小写**，用**连字符 `-`** 连接，确保唯一性。例如：`2025-08-20-chirpy-jekyll-usage-guide.md`。
        
    2. **文章标题（读者友好）**：在 Front Matter 中用 `title` 字段单独设置，可使用**中文、空格和大小写**，以更具可读性。例如：`title: "Chirpy Jekyll 使用指南"`。
        

---

[How to Change the CC-BY license to BY-NC ? · cotes2020/jekyll-theme-chirpy · Discussion #2192 · GitHub](https://github.com/cotes2020/jekyll-theme-chirpy/discussions/2192)
Replace the `_data/locales/en.yml` file.
```
copyright:
  # Shown at the bottom of the post
  license:
    template: 'This post is licensed under :LICENSE_NAME by the author.'
    name: 'CC BY-NC 4.0'
    link: 'https://creativecommons.org/licenses/by-nc/4.0/'

  # Displayed in the footer
  brief: 'Some rights reserved.'
  verbose: >-
    Except where otherwise noted, the blog posts on this site are licensed
    under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License by the author.
```

---

[Chirpy Blog Customization | Huanyu Shi](https://huanyushi.github.io/posts/chirpy-blog-customization/)
---
tags:
  - 学习笔记
---

# 学习笔记

这里记录我的课程学习、读书笔记与知识总结。

## 目录结构建议

- `learning/` 下按主题建立子目录，例如 `python/`、`algorithms/`。
- 每个主题一个 `index.md` 作为该主题的概览页。

## 新建一篇学习笔记

1. 在 `docs/learning/` 下新建一个 `.md` 文件，例如 `docs/learning/python-basics.md`。
2. 在文件开头写 front matter：

    ```yaml
    ---
    tags:
      - 学习笔记
      - Python
    ---
    ```

3. 写正文，保存提交即可。

!!! note "示例"
    可以在这里放公式、代码和图表，例如 $a^2 + b^2 = c^2$。

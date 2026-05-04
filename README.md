# 俄罗斯方块（Tetris）

基于 [Pygame](https://www.pygame.org/) 的桌面版俄罗斯方块小游戏：10×20 场地、七种经典方块、消行计分、预览下一块。

## 环境要求

- Python 3.7+
- [pygame](https://pypi.org/project/pygame/) 2.x

## 安装与运行

```bash
cd 俄罗斯方块
python3 -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install pygame
python3 俄罗斯方块.py
```

若已全局安装 pygame，可直接：

```bash
python3 俄罗斯方块.py
```

## 操作说明

| 按键 | 作用 |
|------|------|
| 任意键 | 开始游戏（主菜单） |
| ← / → | 左右移动 |
| ↑ | 旋转 |
| ↓ | 加速下落 |
| 关闭窗口 | 退出 |

消行得分：每次方块落定后，按本轮消除的行数 `n` 增加 **`n × 10`** 分。堆到顶即游戏结束，屏幕会短暂显示 **YOU LOST**。

## 项目结构

```
俄罗斯方块/
├── 俄罗斯方块.py   # 主程序
├── README.md
└── .gitignore      # 忽略 venv 等本地文件
```

## 许可证

按个人学习/使用需要自行管理；若 fork 或二次发布，请保留对原作者与依赖库的适当说明。

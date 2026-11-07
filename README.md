# zhong-1212

机械工程 / 材料表征方向的工具作者。把工程计算与衍射数据分析做成**可安装、可验证、边界写清楚**的工具，而不是又一层聊天壳。

*Mechanical engineering & materials characterization tooling — installable, verifiable, and honest about its limits.*

---

## 在做什么 · What I build

| 项目 | 是什么 | 给谁用 |
|---|---|---|
| [gradecard-core](https://github.com/zhong-1212/gradecard-core) | 纯 Python 工程计算库：ISO 286 公差配合、硬度/单位换算、轴梁校核、螺栓预紧力、齿轮轴承配合。零第三方依赖，每个结果带 `basis`（标准依据）与 `notes`（适用边界） | 机械工程师、CAD/MES/报价系统后端 |
| [dsh-plugins](https://github.com/zhong-1212/dsh-plugins) | DeepSeek Harness 插件集合，每个插件独立安装 | DSH 用户 |
| `xrd-phase-id` · 在建 | 从两列 2θ-强度文本判物相，每条结论带证据等级（confirmed / probable / weak / positional），单线定相直接拒绝 | 材料、冶金、失效分析 |

## 我对工具的三条要求 · Three rules I hold

1. **结果必须带依据。** 数字后面要跟标准号或案号，不是「模型觉得」。
2. **边界必须写出来。** 不确定就标 `unknown`、标 `weak`、标「不适用」，不把猜测写成事实。
3. **装上就能跑。** 零外部网络出口、零安装期脚本、卸载即净退出。

## 联系 · Contact

- 发现问题请开 Issue，附输入样例与期望输出，比描述更有用。
- English is fine — every project's README has an English section.

<!-- 维护提醒：pin 6 个仓库；bio 与本站描述保持一致；新增仓库后回来更新本表。 -->
# piper_arm

本仓库汇集以下五个项目的默认分支快照，并按原提交展开两个 URDF 子模块。各项目保持独立目录，集合尚未作为统一工程完成编译、仿真或硬件验证。使用前请阅读各项目自带的 README 与环境要求。

| 目录 | 来源 | 精确提交 |
| --- | --- | --- |
| `pyAgxArm` | [agilexrobotics/pyAgxArm](https://github.com/agilexrobotics/pyAgxArm) | `841a625f5f4920e776f20b934eb13048b747e6d0` |
| `agx_arm_ros` | [agilexrobotics/agx_arm_ros](https://github.com/agilexrobotics/agx_arm_ros) | `e4ccec1999279d063c2962030b9437b78b0d0db6` |
| `piper_ros` | [agilexrobotics/piper_ros](https://github.com/agilexrobotics/piper_ros) | `ac41fcbcdda598f01b51cf6175ed9a24d0dacadc` |
| `agx_arm_urdf` | [agilexrobotics/agx_arm_urdf](https://github.com/agilexrobotics/agx_arm_urdf) | `983788b58d7eae76511177f768d85877534917fe` |
| `agx_arm_sim` | [agilexrobotics/agx_arm_sim](https://github.com/agilexrobotics/agx_arm_sim) | `f8cd8b147c75d59e14f90fb0646770eefa268ed0` |
| `agx_arm_sim/agx_arm_description/agx_arm_urdf` | [agilexrobotics/agx_arm_urdf](https://github.com/agilexrobotics/agx_arm_urdf) | `1ee5659d02b33b9379fd647a2e5647800d67f0f4` |
| `agx_arm_ros/src/agx_arm_description/agx_arm_urdf` | [agilexrobotics/agx_arm_urdf](https://github.com/agilexrobotics/agx_arm_urdf) | `983788b58d7eae76511177f768d85877534917fe` |

`agx_arm_ros/src/agx_arm_description/agx_arm_urdf` 使用与顶层 `agx_arm_urdf` 相同的提交。仿真项目使用其原先固定的 URDF 提交。原 `.gitmodules` 文件作为来源内容保留；本集合中的相关目录已包含实际文件，不再是 Git 子模块。

所有原始源码及许可证文件均保留；本集合不改变或重新授予其许可。来源、文件数量、大小、执行权限和 Git LFS 信息见 `SOURCES.json`。

原始文件字节与可执行文件的 `100755` 模式均保留。

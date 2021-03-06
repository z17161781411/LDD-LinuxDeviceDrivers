----------------------------------------------------------------------------------------------------------------

因研究兴趣转移, 个人时间, 精力, 能力有限等原因, 本人不会再有更新, 请见谅.

-----------------------------------------------------------------------------------------------------------------



这个问题挺大的.

2.6 时代跨度非常大, 从2.6.0 (2003年12月发布[36]) 到 2.6.39(2011年5月发布), 跨越了 40 个大版本.
3.0(原计划的 2.6.40, 2011年7月发布) 到 3.19（2015年2月发布）.
4.0（2015年4月发布）到4.2（2015年8月底发布）.


总的来说, 从进入2.6之后, 每个大版本跨度开发时间大概是 2 - 3 个月. 2.6.x , 3.x, 4.x, 数字的递进并没有非常根本性, 非常非常非常引人注目的大变化, 但每个大版本中都有一些或大或小的功能改变. 主版本号只是一个数字而已. 不过要直接从 2.6.x 升级 到 3.x, 乃至 4.x, 随着时间间隔增大, 出问题的机率当然大很多.


个人觉得 Linux 真正走入严肃级别的高稳定性, 高可用性, 高可伸缩性的工业级别内核大概是在 2003 年后吧. 一是随着互联网的更迅速普及, 更多的人使用、参与开发. 二也是社区经过11年发展, 已经慢慢摸索出一套很稳定的协同开发模式, 一个重要的特点是 社区开始使用版本管理工具进入管理, 脱离了之前纯粹手工（或一些辅助的简陋工具）处理代码邮件的方式, 大大加快了开发的速度和力度.


因此, 我汇总分析一下从 2.6.12 (2005年6月发布, 也就是社区开始使用 git 进行管理后的第一个大版本）, 到 4.2 (2015年8月发布)这中间共 **51个大版本**, 时间跨度**10年**的主要大模块的一些重要的变革.


![Linux and 企鹅](https://pic2.zhimg.com/50/db55b324b618d42ad656e52f954cc7ec_hd.jpg)



> 感谢知友 [@costa](https://www.zhihu.com/people/78ceb98e7947731dc06063f682cf9640) 提供无水印题图)


预计内容目录:


| 内容 | GITHUB |
|:---:|:------:|
| **调度子系统(scheduling) [已完成]** | [`SCHEDULER`](https://github.com/gatieme/LDD-LinuxDeviceDrivers/blob/master/study/kernel/00-DESCRIPTION/SCHEDULER.md) |
| **内存管理子系统(memory management) [已完成]** | [`MEMORY_MANAGER`](https://github.com/gatieme/LDD-LinuxDeviceDrivers/blob/master/study/kernel/00-DESCRIPTION/MEMORY_MANAGER.md) |
| **中断与异常子系统(interrupt & exception)[填坑中]** | |
| **时间子系统(timer & timekeeping)** | |
| **同步机制子系统(synchronization)** | |
| **块层(block layer)** | |
| **文件子系统(Linux 通用文件系统层VFS, various fs)** | |
| **网络子系统(networking)** | |
| **调试和追踪子系统(debugging, tracing)** | |
| **虚拟化子系统(kvm)** | |
| **控制组(cgroup)** | |

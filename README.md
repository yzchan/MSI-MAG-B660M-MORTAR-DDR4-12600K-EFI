# MSI-MAG-B660M-MORTAR-DDR4-12600K-EFI
微星B660m迫击炮D4版（不带wifi） + 12600K 黑苹果EFI。

## 配置

| 配置 | 型号 |
| --- | --- |
| CPU | [Intel i5 12600K](https://ark.intel.com/content/www/cn/zh/ark/products/134589/intel-core-i512600k-processor-20m-cache-up-to-4-90-ghz.html) |
| 主板 | [微星MAG B660M MORTAR DDR4](https://cn.msi.com/Motherboard/MAG-B660M-MORTAR-DDR4) |
| 显卡 | [华硕AREZ-RX560-O2G-EVO](https://www.asus.com/motherboards-components/graphics-cards/arez/arez-rx560-o2g-evo/) |
| 内存 | 宇瞻黑豹DDR4 3600 8Gx2 |
| 网卡 | BCM94360CD 4 天线 |
| 硬盘 | [Samsung SSD 970 EVO Plus 500GB](https://www.samsungeshop.com.cn/product/MZ-V7S/MZ-V7S250BW) |
| OC版本 | 0.8.0 |
| macOS | macOS Monterey 12.3.1 (21E258) |
| 机型 | MacPro7,1 |


## BIOS设置

- 关闭CSM（启动模式仅UEFI）
- 关闭快速开机 Fast Boot
- 关闭MSI快速开机
- 关闭Intel VT-D
- 关闭CFG Lock
- 最好屏蔽核显
- 大小核均可开启
- 超线程可开启

## 12代EFI&相关资料

- https://zhuanlan.zhihu.com/p/487736399
- https://github.com/alyxferrari/OpenCore-Install-Guide/blob/alderlake/config.plist/alder-lake.md
- https://github.com/duxphp/Hackintosh-12700KF-B660M-MORTAR-6600XT
- https://github.com/Xmingbai/ASUS-TUF-GAMING-B660M-PLUS-Wi-Fi-D4-Hackintosh
- https://heipg.cn/tutorial/b660m-install-macos.html/comment-page-1
- https://www.bilibili.com/video/BV1nm4y1R7Mh
- https://bbs.pcbeta.com/viewthread-1928907-1-1.html

## Hackintosh学习

- https://blog.daliansky.net/
- https://apple.sqlsec.com/
- https://space.bilibili.com/16323318/channel/collectiondetail?sid=296068
- https://bbs.pcbeta.com/forum.php?gid=86
- https://www.tonymacx86.com/
- https://github.com/daliansky/OC-little

## Tools

- [OC Auxiliary Tools](https://github.com/ic005k/QtOpenCoreConfig)
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [Hackintool](https://github.com/headkaze/Hackintool)
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html)
- [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg)

## 更新记录

### 2022-05-30
使用SSDTTime提取了SSDT，重新编译了EC-USBX.aml

### 2022-05-21

- 定制了USB，睡眠久一点需要按电源键才能唤醒
- 隔空投送正常，通用控制也可以使用
- Geekbench5跑分正常（单核1970，多核11290）

### 2022-05-18
正常进入系统，蓝牙、wifi、声卡、网卡正常。appid登录正常。其他功能待测试。

# 使用AD9834与STM32联调的函数信号发生器

## 项目描述

本资源文件提供了一个基于STM32F103RCT6微控制器和AD9834芯片的函数信号发生器的设计与实现。该信号发生器能够生成多种波形，包括正弦波、方波和三角波，并且支持频率范围的灵活调整。

## 功能特点

- **控制芯片**：STM32F103RCT6
- **时钟频率**：75MHz
- **波形输出**：
  - **正弦波**：频率范围0-30MHz（可编辑至0-100MHz）
  - **方波**：频率范围50kHz-5MHz
  - **三角波**：频率范围0-10MHz
- **扫频功能**：默认输出正弦波
- **显示模块**：12864液晶显示屏

## 使用说明

1. **硬件连接**：
   - 将STM32F103RCT6与AD9834按照电路图进行连接。
   - 连接12864液晶显示屏以显示当前波形和频率信息。

2. **软件配置**：
   - 下载并烧录提供的固件到STM32F103RCT6。
   - 根据需要调整代码中的频率范围和波形类型。

3. **操作步骤**：
   - 上电后，系统将自动初始化并显示当前波形和频率。
   - 通过按键或编码器调整频率和波形类型。

## 注意事项

- 在调整频率范围时，请确保不超过AD9834的工作频率限制。
- 确保所有硬件连接正确，避免短路或接触不良。

## 资源文件内容

- **源代码**：包含STM32的固件代码。
- **电路图**：详细的硬件连接图。
- **使用手册**：详细的操作说明和参数调整指南。

## 贡献与反馈

欢迎对该项目进行改进和优化，如果您有任何问题或建议，请在GitHub仓库中提交Issue或Pull Request。

---

希望本资源文件能够帮助您快速实现一个功能强大的函数信号发生器！

## 下载链接
[使用AD9834与STM32联调的函数信号发生器](https://pan.quark.cn/s/dfe1fb0fbccd) 

(备用: [备用下载](https://pan.baidu.com/s/10eTHaWUXV3qnTAJoOVBtsQ?pwd=1234))

## 说明

该仓库仅用于学习交流，请勿用于商业用途。

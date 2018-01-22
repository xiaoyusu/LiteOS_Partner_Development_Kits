# 物联网俱乐部IoTClub开发套件

### 一、简介

![](./about_us/iotclub_1.png)

EVB_M1是以STM32L4为主控MCU，BC95为通讯模组的NB-IoT开发板。丰富的板载资源，以及超低功耗的硬件选型。开发板以小巧的设计，板载OLED、电池供电、eSIM等多种特色功能。

- 软件特色

- 本开发板具有完整的生态链：提供系统支持、驱动支持、服务器测试以及平台对接支持
- 系统支持：开发板支持Huawei LiteOS操作系统（已移植）
- 驱动支持：提供AT指令驱动，以及板载设备驱动
- 服务器测试：提供连接服务器收发数据测试学习
- 平台对接：提供开发板接入Oceanconnet 程序


### 二、规格

- 基本信息

| 项目 |	内容 |
| ----  |   ---- |
| 电源接口 | 6V - 24V |
|锂电池	|3.7V   7号电池|
|Mini-USB|	默认波特率9600,1位停止位，8位数据位，无校验位|
|MCU|	STM32L431Rx，Cortex®-M4，80MHz|
|OLED	|分辨率128×32，蓝色|
|NB模组|	移远BC95-HB|
|支持频段|	电信B5，移动/联通B8，海外B20|
|发射功率|	23dBm（Max）|
|接收灵敏度|	-129dBm|
|天线端口|	标准SMA阴头天线接口|
|功耗|	2mA - 300mA|
|功能支持|	支持数据上报，接收下发，液晶显示，SIM芯片卡，按键输入，仿真调试|
|可扩展接口*|	温湿度、烟感、GPS、地磁检测、三轴加速度等|
|扩展板|	支持定制|
|尺寸|	12cm * 8cm|
|重量|	450-500g|
|工作温度|	-40℃~80℃|

- 包装内容

| 序号 |	内容 |数量 |
| ----  |   ---- |  ---- |
|1	|EVB_M1底板（带BC95模组）|	1|
|2|	AC-DC电源	|1|
|3|	EVB_EXT扩展板|	1|
|4|	跳帽（黄色）	|2|
|5|	跳帽（白色）	|1|
|6|	ST-Link（下载器）	|1|
|7|	杜邦线	|4|
|8|	天线（3dB）|	1|
|9|	铜柱	|4|
|10	|包装盒	|1|


### 三、资源获取(请参考kit_docs文件夹中资料、教程、源码)

源码Demo

- [EVB_M1 demo介绍](./kit_docs/03. 源码/demo介绍.docx)
- [EVB_M1_Code_LiteOS](./kit_docs/03. 源码/EVB_M1_Code_LiteOS.zip)
- [EVB_M1_Code_Demo](./kit_docs/03. 源码/EVB_M1_Code_Demo.zip)

原理图

- [EVB_M1 PCB图](./kit_docs/01. 资料/EVB_M1 PCB图.pdf)
- [EVB_M1 V2.0原理图](./kit_docs/01. 资料/EVB_M1 V2.0原理图.pdf)

开发指南

- [EVB_M1 介绍](./kit_docs/01. 资料/EVB_M1介绍（新）.docx)
- [EVB_M1串口调试NB-IoT入门篇](./kit_docs/02. 教程/EVB_M1串口调试NB-IoT入门篇.doc)
- [EVB_M1硬件介绍](./kit_docs/02. 教程/EVB_M1硬件.docx)
- [华为OceanConnect IoT平台接入手册](./kit_docs/02. 教程/华为平台接入手册.docx)

工具（请自行至官方渠道下载）

- STLINK驱动
- STM32 ST-LINK Utility v4.0.0 setup
- stm32cubemx
- 串口驱动-CH340_Windows

# EHS IOT Laboratory Manage System

上海科技大学实验室物联网管理系统

> 曾经是实验室气瓶项目组，现改名为实验室物联网项目

#### 项目介绍

这个项目是一个基于物联网技术的实验室设备管理系统，通过自组网技术，实现了低功耗、分布式的设备管理。该系统包括终端机、网关、服务器和工控机四个部分，其中终端机作为物联网节点，通过Zigbee自组网技术与网关进行通信，实现了设备状态的实时采集和更新，然后通过墨水瓶显示屏进行展示。同时，该系统还具备灵活性，可以根据实验室需求随时扩展或调整设备。

这个项目的核心是物联网技术，通过物联网的连接，可以实现设备状态的实时监测和数据的采集，从而实现对设备的精细化管理。同时，自组网技术和低功耗分布式设计，可以实现设备之间的互联和无缝切换，提高系统的可靠性和稳定性。

#### 项目要求

* 终端
  * Zigbee自组网
  * 低功耗，分布式
  * 墨水瓶显示
* 网关
* 服务器
  * Linux系统，运行一些服务
* 工控机
  * 安卓系统，带触摸屏/键鼠
  * 有简易界面，放在实验室用于交互

#### 研发内容

* 终端机
  * 主控
    * Arduino (Atmel)
    * RP2040
    * ESP32
    * NRF528xx
  * 无线
    * 蓝牙
    * WIFI
    * Zigbee
    * 2.4G 其他协议
  * 显示
    * 2.9寸三色墨水屏
  * 供电
    * 电池供电模块设计
    * 电源转换模块设计
  * 主板
  * 其他
* 网关
  * 主控
    * ESP32
    * 其他x86
  * 无线
    * 同终端机
  * 有线
    * USB串口
    * 网口有线接入
  * 显示（可选）
  * 其他
* 服务器
  * Linux服务
    * 软件开发
    * UI设计
    * API接口
    * 人机交互
* 工控机
  * 安卓终端
    * 软件开发
    * UI设计
    * API接口
    * 人机交互

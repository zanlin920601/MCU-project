---
layout: post
title: PID 遙控小車
author: [Kevin Chuang]
category: [Lecture]
tags: [jekyll, ai]
---

## PID 遙控小車
![](https://github.com/rkuo2023/MCU-project/blob/main/images/ESP32_RoboCar.jpg?raw=true)

### 設計考量與相關技術
**系統設計考量：**<br>
1. 操作方式:藍牙遙控手機App
2. 移動方式:兩輪 
3. 供電方式:鋰電池 3.7V x2
4. 聯網方式:藍牙

**所需相關技術：**
1. MIT App Inventor 2 手機程式設計 
2. Arduino程式設計
3. DRV8833 馬達驅動

**所需相關套件:**
![](https://image.ruten.com.tw/g2/8/d4/16/21440347657238_872.jpg)

### 系統方塊圖
![](https://github.com/zanlin920601/MCU-project/blob/main/images/PID.jpg?raw=true)

### 程式碼
![](https://github.com/zanlin920601/MCU-project/blob/main/images/06031.png?raw=true)
![](https://github.com/zanlin920601/MCU-project/blob/main/images/06032.png?raw=true)
![](https://github.com/zanlin920601/MCU-project/blob/main/images/06033.png?raw=true)
![](https://github.com/zanlin920601/MCU-project/blob/main/images/06034.png?raw=true)
![](https://github.com/zanlin920601/MCU-project/blob/main/images/06035.png?raw=true)

### 實作影片
**老師您好，我已更新心跳血氧偵測器、ESP32慣性元件之方塊圖，拜託老師再次查閱了🙏；
另外我在作業區沒有放到IoT Thinkspeak的作業連結，在此補上
* [IoT Thinkspeak](https://zanlin920601.github.io/MCU-project/lecture/2023/05/25/IoT-Thinkspeak.com.html)
還麻煩老師查閱，辛苦老師這學期的教學了！

<iframe width="455" height="809" src="https://www.youtube.com/embed/T3rrhD6HWUM" title="PID小車" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*

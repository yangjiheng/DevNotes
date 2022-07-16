# Development Related Notes

## Table of Content
- **[System Environment](#system-environment)**
    - **[Ubuntu](#ubuntu-development-environment)**
    - **[nVidia Jetson](#nvidia-jetson)**
- **[Native Client Development](#native-client-development)**
    - **[QT Tech](#qt-related)**
- **[Data Analysis](#data-analysis)**
    - **[Firebase](#firebase)**
---

## System Environment

### Ubuntu Development Environment

* Solving -lGL unsupported:  <a target=_blank href="https://gist.github.com/yangjiheng/4a6d6f5279306d88a88c7256da1a55a6">Code Gist</a>
* Solving -lz unsupported:  <a target=_blank href="https://gist.github.com/yangjiheng/135eb7402fc4d861381f35c81317e60d">Code Gist</a>

### nVidia Jetson
* Install JetPack on Jetson: <a target="_blank" href="https://developer.nvidia.com/embedded/jetpack">Official Website</a>. A host Linux machine and the target HW device is required (preferrably connected with a micro-USB cable). Then JetPack can be install via nVidia SDK Manager.

## Native Client Development

### QT Related

* Install QT on Ubuntu, especially on ARM 64, where there is no prebuilt all-in-one install files: <a href="https://gist.github.com/yangjiheng/32ab1adabb5d2961bc695f3763914bc2">Code Gist</a>
* Check is a QString is number: <a target=_blank href="https://gist.github.com/yangjiheng/d3313b7caa62b21ff4c04eb82264fcea">Code Gist</a>

## Data Analysis

### Firebase

- Configure BigQuery with Google Analytics and Firebase.
  - Actually lots of details, you can refer to: <a href="https://dataenthusiast.it/english-version/how-to-link-google-analytics-4-to-bigquery/">This Tutorial</a> for details, especially IAM settings can really be easy to miss.
  - You need to wait to upto 24 hours to get data synced, which is also misleading.
# About This Repository

This repository is used to development related issues/findings as we march forward. It's not meant to be systematic, but more like random gems collected. Contact me if you want to connect with me:

* WeChat: jiheng_yang
* Discord: https://discord.gg/hgwZHpcK
* Email: jiheng.yang@gmail.com


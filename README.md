# Wocyber_A2

飞牛 A2（TV27 板型）固件镜像仓库。固件以压缩包形式发布在 **Releases** 中。

## 固件下载

从 [Releases](https://github.com/zm51432/Wocyber_A2/releases) 下载：

- `fnOS_A2.img.gz`（约 1.8 GB，解压后为 `fnOS_A2.img`，原始镜像 3.6 GB）

## 使用步骤

1. 从 Releases 下载 `fnOS_A2.img.gz`
2. 校验（推荐）：`md5sum fnOS_A2.img.gz` 应与 `CHECKSUMS.txt` 中对应值一致
3. 解压：`gunzip fnOS_A2.img.gz` → 得到 `fnOS_A2.img`
4. 烧录到 A2（TV27）设备
5. 解压后校验：`md5sum fnOS_A2.img` 应与 `CHECKSUMS.txt` 中对应值一致

## 校验和

资产 `CHECKSUMS.txt` 包含 `fnOS_A2.img.gz` 与 `fnOS_A2.img` 的 md5，下载后可逐项核对。

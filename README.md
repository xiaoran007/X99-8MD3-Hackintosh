# X99-8MD3-Hackintosh

## OpenCore version 1.0.0
[![macOS](https://img.shields.io/badge/macOS-Monterey-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Ventura-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Sonoma-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.0-blue)](https://github.com/acidanthera/OpenCorePkg)

# ⚠️ Change System code(SSN,UUID,ROM) FIRST.

## Hardware

|                     | Specifications               | Note |
| ------------------- |:---------------------------------:|:---------:|
| Device:     | X99-8MD3                 |  /  |
| Motherboard:     | Intel C612                 | May not work for X99 chipset   |
| CPU:            | E5-2673 V3                          | Xeon E5 V3 CPU   |
| dGPU:            | AMD Radeon RX Vega 64 8GB                          | /   |
| Hard Drive:      | WD SN730 512GB          |  M2 Nvme         | 
| RAM:             | 16GB DDR3 1600 RECC * 2        |  32 GB in total         |
| Wireless Card: | BCM94360cs2                   | Apple version from iMac     |
| Power:           | 650W ATX power adapter |  /         |

---

## Suggestion
For the best experience, macOS 13 Ventura is recommended. Here is the simple reason.

Although the current OC version supports macOS 14 Sonoma, Apple already removed all BCM wireless card support (not usable at all). So if you plan to install macOS 14, you must use Intel wireless cards for example ax200. According to the current Intel wireless driver, AirDrop is still not usable.

Therefore, if you want to use Airdrop, the only choice is to use a BCM wireless card and macOS 13 Ventura.


## Compatibilities 
This EFI is modified for the X99 8MD3 motherboard. In theory, all Xeon E5v3 CPUs with C612 chipset are compatible with this EFI. You may need to modify USB mapping and wireless card settings.

## Operational state 
### Working：

- DP and HDMI ports on Radeon RX Vega 64  
- Metal 3 enable
- HiDpi with 4K output
- Audio output on DP  
- All USB ports  
- Wi-Fi & Bluetooth  
- Airdrop  
- AirPlay  
- Continuity  

### Not working:

- None

### Not tested yet:

- None 

## Some images:

#### device information
![device info](./imgs/device_info.png)

#### Bluetooth
![bluetooth](./imgs/bt.png)

#### WIFI
![wifi](./imgs/wifi.png)

#### Airdrop
![airdrop](./imgs/airdrop.png)

#### dGPU Metal
![GPU](./imgs/metal.png)

#### Disk Speed
![Disk](./imgs/disk_speed.png)


# STM32F429ZI_initial_template

An initial project for STM32F429ZI (aka STM32F429I-Disco1). Is uses LL but no HAL. Some macros that use Bit Band machinery are added. It is very useful for developing high speed and peripheral concurrent firmware.
Visual Studio Code with Cortex-Debug extension was used as an IDE as well as arm-non-aebi-gcc, make (in MacOS, while in Windows OS mingw32-make was used), openocd, stutils, st-link drivers.

- gcc-arm-none-eabi-5_4-2016q3-20160926-win32.zip
- mingw-w64-v7.0.0.zip
- stlink-1.3.0-win64.zip
- openocd-20200114.7z
- en.stsw-link009.zip

In MacOs was taken Homebrew (https://brew.sh/) for packages installing.
YandexDisk was taken as Cloud storage for file synchronization.

Thanks to Cristian Dobre for his article https://hbfsrobotics.com/blog/configuring-vs-code-arm-development-stm32cubemx

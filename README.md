# EUPMAccess

Works only on x64 version of Windows 7, 8, 8.1, 10 included
This patch your current session to allow any application to open a handle to \Device\PhysicalMemory and do kernel manipulation from usermode (Without the risk of BSOD)

Compatible only with 64 bits version of Windows 7, Windows 8, Windows 8.1 and Windows 10.

Usage: (IMPORTANT, FOLLOW THIS)
0) Close any game/ac
1) place ASMMAP64.SYS in the same folder as the .bat
2) Launch the bat AS ADMINISTRATOR
3) Compile the exploit as x64, release
4) Lauch the exploit AS ADMINISTRATOR

--- If it says success :
5) Press any key to close the exploit
6) Close the bat window by pressing any key
7)You can now open Physical Memory from your code by using NtOpenSection on \Device\PhysicalMemory

--- If it fails
5) Post logs + windows version.

credit: @sammy & @mistree for bugchecking for me on Windows 7

https://github.com/waryas/EUPMAccess

https://www.unknowncheats.me/forum/anti-cheat-bypass/239692-dkom-allow-process-read-physical-memory-driver.html

# Woothosting Cloud Resource Pool Starter
```
Cost :                    $36.00/yr
Type :                    OpenVZ
Max VPS :                 2
Max Users :               2
Max Memory :              4 GB
Max Burst Memory / Swap : 8 GB
Max Bandwidth :           3.91 TB
Max IPv4 :                2
Max IPv6 :                300
```

## Miami Location (Ubuntu 16.04 x64 Fully Updated)
```
curl ipinfo.io | tee ipinfo.log
{
  "ip": "104.223.87.xxxx",
  "hostname": "104.223.87.xxxx.static.quadranet.com",
  "city": "Miami",
  "region": "Florida",
  "country": "US",
  "loc": "25.7806,-80.1826",
  "postal": "33132",
  "phone": "305",
  "org": "AS8100 QuadraNet, Inc"
}

(curl -s wget.racing/nench.sh | bash; curl -s wget.racing/nench.sh | bash) 2>&1 | tee nench.log
-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:02:18 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU           E5620  @ 2.40GHz
CPU cores:    4
Frequency:    2400.122 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab123.3 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    5.491 seconds
CPU: bzip2-compressing 500 MB
    10.009 seconds
CPU: AES-encrypting 500 MB
    4.463 seconds

ioping: seek rate
    min/avg/max/mdev = 764 ns / 80.1 us / 288.9 ms / 2.39 ms
ioping: sequential read speed
    generated 9.90 k requests in 5.00 s, 2.42 GiB, 1.98 k iops, 495.0 MiB/s

dd: sequential write speed
    1st run:    734.33 MiB/s
    2nd run:    103.00 MiB/s
    3rd run:    413.89 MiB/s
    average:    417.07 MiB/s

IPv4 speedtests
    your IPv4:    104.223.87.xxxx

    Cachefly CDN:         14.55 MiB/s
    Leaseweb (NL):        1.12 MiB/s
    Softlayer DAL (US):   1.03 MiB/s
    Online.net (FR):      0.96 MiB/s
    OVH BHS (CA):         1.00 MiB/s

IPv6 speedtests
    your IPv6:    2607:ff48:aa81:xxxx

    Leaseweb (NL):        2.40 MiB/s
    Softlayer DAL (US):   1.48 MiB/s
    Online.net (FR):      1.46 MiB/s
    OVH BHS (CA):         2.21 MiB/s
-------------------------------------------------

-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:04:33 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU           E5620  @ 2.40GHz
CPU cores:    4
Frequency:    2400.122 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab123.3 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    5.230 seconds
CPU: bzip2-compressing 500 MB
    8.655 seconds
CPU: AES-encrypting 500 MB
    4.562 seconds

ioping: seek rate
    min/avg/max/mdev = 683 ns / 71.7 us / 102.7 ms / 979.9 us
ioping: sequential read speed
    generated 10.2 k requests in 5.00 s, 2.49 GiB, 2.04 k iops, 510.1 MiB/s

dd: sequential write speed
    1st run:    402.45 MiB/s
    2nd run:    140.19 MiB/s
    3rd run:    238.42 MiB/s
    average:    260.35 MiB/s

IPv4 speedtests
    your IPv4:    104.223.87.xxxx

    Cachefly CDN:         18.11 MiB/s
    Leaseweb (NL):        1.16 MiB/s
    Softlayer DAL (US):   0.66 MiB/s
    Online.net (FR):      0.51 MiB/s
    OVH BHS (CA):         0.56 MiB/s

IPv6 speedtests
    your IPv6:    2607:ff48:aa81:xxxx

    Leaseweb (NL):        1.08 MiB/s
    Softlayer DAL (US):   0.99 MiB/s
    Online.net (FR):      0.46 MiB/s
    OVH BHS (CA):         1.46 MiB/s
-------------------------------------------------
```

## LAX Location (Ubuntu 16.04 x64 Fully Updated)
```
curl ipinfo.io | tee ipinfo.log
{
  "ip": "104.223.49.xxxx",
  "hostname": "104.223.49.xxxx.static.quadranet.com",
  "city": "Los Angeles",
  "region": "California",
  "country": "US",
  "loc": "34.0438,-118.2510",
  "postal": "90014",
  "phone": "213",
  "org": "AS8100 QuadraNet, Inc"
}

(curl -s wget.racing/nench.sh | bash; curl -s wget.racing/nench.sh | bash) 2>&1 | tee nench.log
-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:15:43 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU           E5620  @ 2.40GHz
CPU cores:    4
Frequency:    2393.837 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab133.1 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    33.308 seconds
CPU: bzip2-compressing 500 MB
    41.675 seconds
CPU: AES-encrypting 500 MB
    4.997 seconds

ioping: seek rate
    min/avg/max/mdev = 2.12 us / 75.1 us / 120.7 ms / 905.4 us
ioping: sequential read speed
    generated 6.46 k requests in 5.00 s, 1.58 GiB, 1.29 k iops, 322.8 MiB/s

dd: sequential write speed
    1st run:    187.87 MiB/s
    2nd run:    238.42 MiB/s
    3rd run:    245.09 MiB/s
    average:    223.80 MiB/s

IPv4 speedtests
    your IPv4:    104.223.49.xxxx

    Cachefly CDN:         47.15 MiB/s
    Leaseweb (NL):        3.76 MiB/s
    Softlayer DAL (US):   4.65 MiB/s
    Online.net (FR):      4.29 MiB/s
    OVH BHS (CA):         9.34 MiB/s

IPv6 speedtests
    your IPv6:    2607:fcd0:106:xxxx

    Leaseweb (NL):        3.54 MiB/s
    Softlayer DAL (US):   10.89 MiB/s
    Online.net (FR):      3.39 MiB/s
    OVH BHS (CA):         6.12 MiB/s
-------------------------------------------------

-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:18:54 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU           E5620  @ 2.40GHz
CPU cores:    4
Frequency:    2393.837 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab133.1 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    22.847 seconds
CPU: bzip2-compressing 500 MB
    31.741 seconds
CPU: AES-encrypting 500 MB
    5.296 seconds

ioping: seek rate
    min/avg/max/mdev = 2.21 us / 69.6 us / 20.2 ms / 244.2 us
ioping: sequential read speed
    generated 10.7 k requests in 5.00 s, 2.62 GiB, 2.15 k iops, 537.0 MiB/s

dd: sequential write speed
    1st run:    246.05 MiB/s
    2nd run:    236.51 MiB/s
    3rd run:    203.13 MiB/s
    average:    228.56 MiB/s

IPv4 speedtests
    your IPv4:    104.223.49.xxxx

    Cachefly CDN:         41.58 MiB/s
    Leaseweb (NL):        2.29 MiB/s
    Softlayer DAL (US):   22.62 MiB/s
    Online.net (FR):      3.14 MiB/s
    OVH BHS (CA):         4.01 MiB/s

IPv6 speedtests
    your IPv6:    2607:fcd0:106:xxxx

    Leaseweb (NL):        3.72 MiB/s
    Softlayer DAL (US):   14.97 MiB/s
    Online.net (FR):      5.71 MiB/s
    OVH BHS (CA):         6.31 MiB/s
-------------------------------------------------
```

## NY Location (Ubuntu 16.04 x64 Fully Updated)
```
curl ipinfo.io | tee ipinfo.log
{
  "ip": "192.210.160.xxxx",
  "hostname": "192-210-160-xxxx-host.colocrossing.com",
  "city": "Buffalo",
  "region": "New York",
  "country": "US",
  "loc": "42.8864,-78.8781",
  "postal": "14202",
  "org": "AS36352 ColoCrossing"
}

(curl -s wget.racing/nench.sh | bash; curl -s wget.racing/nench.sh | bash) 2>&1 | tee nench.log
-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:25:27 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU E5-2620 0 @ 2.00GHz
CPU cores:    4
Frequency:    2001.000 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab123.9 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    6.314 seconds
CPU: bzip2-compressing 500 MB
    9.692 seconds
CPU: AES-encrypting 500 MB
    2.196 seconds

ioping: seek rate
    min/avg/max/mdev = 1.48 us / 63.4 us / 26.8 ms / 437.0 us
ioping: sequential read speed
    generated 11.4 k requests in 5.00 s, 2.79 GiB, 2.29 k iops, 572.2 MiB/s

dd: sequential write speed
    1st run:    197.41 MiB/s
    2nd run:    802.99 MiB/s
    3rd run:    748.63 MiB/s
    average:    583.01 MiB/s

IPv4 speedtests
    your IPv4:    192.210.160.xxxx

    Cachefly CDN:         29.07 MiB/s
    Leaseweb (NL):        0.64 MiB/s
    Softlayer DAL (US):   2.08 MiB/s
    Online.net (FR):      1.09 MiB/s
    OVH BHS (CA):         2.28 MiB/s

No IPv6 connectivity detected
-------------------------------------------------

-------------------------------------------------
 nench.sh v2018.04.14 -- https://git.io/nench.sh
 benchmark timestamp:    2018-08-30 17:26:55 UTC
-------------------------------------------------

Processor:    Intel(R) Xeon(R) CPU E5-2620 0 @ 2.00GHz
CPU cores:    4
Frequency:    2001.000 MHz
RAM:          2.0G
Swap:         2.0G
Kernel:       Linux 2.6.32-042stab123.9 x86_64

Disks:
Filesystem     Type      Size Inodes
/dev/simfs     simfs      30G    15M

CPU: SHA256-hashing 500 MB
    6.694 seconds
CPU: bzip2-compressing 500 MB
    9.656 seconds
CPU: AES-encrypting 500 MB
    2.235 seconds

ioping: seek rate
    min/avg/max/mdev = 1.04 us / 58.2 us / 28.9 ms / 356.1 us
ioping: sequential read speed
    generated 11.4 k requests in 5.00 s, 2.77 GiB, 2.27 k iops, 567.7 MiB/s

dd: sequential write speed
    1st run:    273.70 MiB/s
    2nd run:    210.76 MiB/s
    3rd run:    628.47 MiB/s
    average:    370.98 MiB/s

IPv4 speedtests
    your IPv4:    192.210.160.xxxx

    Cachefly CDN:         28.61 MiB/s
    Leaseweb (NL):        1.48 MiB/s
    Softlayer DAL (US):   1.29 MiB/s
    Online.net (FR):      1.51 MiB/s
    OVH BHS (CA):         3.32 MiB/s

No IPv6 connectivity detected
-------------------------------------------------
```

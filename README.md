# x15-pkt-engine

## Synopsis

Linux kernel eBPF byte-code compiler for TI AM5728 network packet engine

## Code Example

Loadable kernel module that compiles eBPF byte-code to AM5728 packet engine binary code.

## Motivation

This driver provides hardware packet engine acceleration for the eBPF byte-code compiler 
in the Linux kernel to accelerate userspace application libraries such as libpcap, tcpdump and 
applications like Snort and Suricata.

## Installation

Kernel patch for 4.1.x and forward.

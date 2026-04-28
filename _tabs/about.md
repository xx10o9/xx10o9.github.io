---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

Security researcher with ~4 years in offensive security and vulnerability research, focused on **kernel exploitation**, **reverse engineering**, and **coverage-guided fuzzing** across macOS/iOS and Linux. Currently extending the kernel work into firmware and embedded security.

## What I work on

- **iOS / macOS internals** — XNU kernel architecture, Mach IPC, IOKit and UserClients, kernel extensions, entitlements, sandboxing, code signing, dyld, Mach-O. Reversing fully stripped binaries to recover control flow and data structures using static and dynamic analysis.
- **Linux kernel internals** — memory management, page allocator, slab/slub, namespaces, pipefs, `core_pattern`. Mitigation analysis around SMEP, SMAP, KASLR, and KPTI; cross-cache heap exploitation strategies.
- **Coverage-guided fuzzing** — LibFuzzer and LibAFL harnesses targeting kernel and system-level components.
- **Exploit reproductions** — re-implemented Dirty Pipe, Dirty Page Table, and RetSpill on hardened kernels to study mitigation interactions.
- **Crash analysis** — root-cause analysis of iOS/macOS panics from the panic string and Linux kernel Oops/panic traces.

## What this blog is

Notes, writeups, and project logs as I work through hands-on builds in firmware reverse engineering, embedded exploitation, and fuzzing — extending kernel security work into the embedded/firmware side.

## Toolchain

C · C++ · Python · Bash · x86-64 and ARM assembly · IDA Pro · LLDB · GDB · QEMU/KVM · KASAN · KFENCE · ftrace · perf · strace · objdump · readelf

## Contact

[GitHub](https://github.com/xx10o9) · [X](https://x.com/x_x10o9)

# drill0

64-bit x86_64 kernel written from scratch.  
no libc. no rust. no handouts.

currently running deeper than your distro ever will.

## features
- multiboot2 + long mode
- identity-mapped paging
- vga text mode with ansi colors
- ps/2 keyboard driver (you can type)
- idt + basic isr
- kernel panic with stack trace

## build & run
```bash
make run        # qemu + serial output
make debug      # qemu + gdb stub on port 1234

# .asm
disassembled output attempt using objdump

a.out:     file format elf64-x86-64
architecture: i386:x86-64, flags 0x00000150:
HAS_SYMS, DYNAMIC, D_PAGED
start address 0x0000000000001060

Contents of section .interp:
 0318 2f6c6962 36342f6c 642d6c69 6e75782d  /lib64/ld-linux-
 0328 7838362d 36342e73 6f2e3200           x86-64.so.2.    
Contents of section .note.gnu.property:
 0338 04000000 10000000 05000000 474e5500  ............GNU.
 0348 020000c0 04000000 03000000 00000000  ................
Contents of section .note.gnu.build-id:
 0358 04000000 14000000 03000000 474e5500  ............GNU.
 0368 f3b52b00 a107b81b 8c72abb2 577cea45  ..+......r..W|.E
 0378 bd29ef6d                             .).m            
Contents of section .note.ABI-tag:
 037c 04000000 10000000 01000000 474e5500  ............GNU.
 038c 00000000 03000000 02000000 00000000  ................
Contents of section .gnu.hash:
 03a0 02000000 06000000 01000000 06000000  ................
 03b0 00008100 00000000 06000000 00000000  ................
 03c0 d165ce6d                             .e.m            
Contents of section .dynsym:
 03c8 00000000 00000000 00000000 00000000  ................
 03d8 00000000 00000000 3f000000 20000000  ........?... ...
 03e8 00000000 00000000 00000000 00000000  ................
 03f8 0b000000 12000000 00000000 00000000  ................
 0408 00000000 00000000 21000000 12000000  ........!.......
 0418 00000000 00000000 00000000 00000000  ................
 0428 5b000000 20000000 00000000 00000000  [... ...........
 0438 00000000 00000000 6a000000 20000000  ........j... ...
 0448 00000000 00000000 00000000 00000000  ................
 0458 12000000 22000000 00000000 00000000  ...."...........
 0468 00000000 00000000                    ........        
Contents of section .dynstr:
 0470 006c6962 632e736f 2e360070 72696e74  .libc.so.6.print
 0480 66005f5f 6378615f 66696e61 6c697a65  f.__cxa_finalize
 0490 005f5f6c 6962635f 73746172 745f6d61  .__libc_start_ma
 04a0 696e0047 4c494243 5f322e32 2e35005f  in.GLIBC_2.2.5._
 04b0 49544d5f 64657265 67697374 6572544d  ITM_deregisterTM
 04c0 436c6f6e 65546162 6c65005f 5f676d6f  CloneTable.__gmo
 04d0 6e5f7374 6172745f 5f005f49 544d5f72  n_start__._ITM_r
 04e0 65676973 74657254 4d436c6f 6e655461  egisterTMCloneTa
 04f0 626c6500                             ble.            
Contents of section .gnu.version:
 04f4 00000000 02000200 00000000 0200      ..............  
Contents of section .gnu.version_r:
 0508 01000100 01000000 10000000 00000000  ................
 0518 751a6909 00000200 33000000 00000000  u.i.....3.......
Contents of section .rela.dyn:
 0528 b83d0000 00000000 08000000 00000000  .=..............
 0538 40110000 00000000 c03d0000 00000000  @........=......
 0548 08000000 00000000 00110000 00000000  ................
 0558 08400000 00000000 08000000 00000000  .@..............
 0568 08400000 00000000 d83f0000 00000000  .@.......?......
 0578 06000000 01000000 00000000 00000000  ................
 0588 e03f0000 00000000 06000000 03000000  .?..............
 0598 00000000 00000000 e83f0000 00000000  .........?......
 05a8 06000000 04000000 00000000 00000000  ................
 05b8 f03f0000 00000000 06000000 05000000  .?..............
 05c8 00000000 00000000 f83f0000 00000000  .........?......
 05d8 06000000 06000000 00000000 00000000  ................
Contents of section .rela.plt:
 05e8 d03f0000 00000000 07000000 02000000  .?..............
 05f8 00000000 00000000                    ........        
Contents of section .init:
 1000 f30f1efa 4883ec08 488b05d9 2f000048  ....H...H.../..H
 1010 85c07402 ffd04883 c408c3             ..t...H....     
Contents of section .plt:
 1020 ff359a2f 0000f2ff 259b2f00 000f1f00  .5./....%./.....
 1030 f30f1efa 68000000 00f2e9e1 ffffff90  ....h...........
Contents of section .plt.got:
 1040 f30f1efa f2ff25ad 2f00000f 1f440000  ......%./....D..
Contents of section .plt.sec:
 1050 f30f1efa f2ff2575 2f00000f 1f440000  ......%u/....D..
Contents of section .text:
 1060 f30f1efa 31ed4989 d15e4889 e24883e4  ....1.I..^H..H..
 1070 f050544c 8d056601 0000488d 0def0000  .PTL..f...H.....
 1080 00488d3d c1000000 ff15522f 0000f490  .H.=......R/....
 1090 488d3d79 2f000048 8d05722f 00004839  H.=y/..H..r/..H9
 10a0 f8741548 8b052e2f 00004885 c07409ff  .t.H.../..H..t..
 10b0 e00f1f80 00000000 c30f1f80 00000000  ................
 10c0 488d3d49 2f000048 8d35422f 00004829  H.=I/..H.5B/..H)
 10d0 fe4889f0 48c1ee3f 48c1f803 4801c648  .H..H..?H...H..H
 10e0 d1fe7414 488b0505 2f000048 85c07408  ..t.H.../..H..t.
 10f0 ffe0660f 1f440000 c30f1f80 00000000  ..f..D..........
 1100 f30f1efa 803d052f 00000075 2b554883  .....=./...u+UH.
 1110 3de22e00 00004889 e5740c48 8b3de62e  =.....H..t.H.=..
 1120 0000e819 ffffffe8 64ffffff c605dd2e  ........d.......
 1130 0000015d c30f1f00 c30f1f80 00000000  ...]............
 1140 f30f1efa e977ffff fff30f1e fa554889  .....w.......UH.
 1150 e5488d3d ac0e0000 b8000000 00e8eefe  .H.=............
 1160 ffffb800 0000005d c30f1f80 00000000  .......]........
 1170 f30f1efa 41574c8d 3d3b2c00 00415649  ....AWL.=;,..AVI
 1180 89d64155 4989f541 544189fc 55488d2d  ..AUI..ATA..UH.-
 1190 2c2c0000 534c29fd 4883ec08 e85ffeff  ,,..SL).H...._..
 11a0 ff48c1fd 03741f31 db0f1f80 00000000  .H...t.1........
 11b0 4c89f24c 89ee4489 e741ff14 df4883c3  L..L..D..A...H..
 11c0 014839dd 75ea4883 c4085b5d 415c415d  .H9.u.H...[]A\A]
 11d0 415e415f c366662e 0f1f8400 00000000  A^A_.ff.........
 11e0 f30f1efa c3                          .....           
Contents of section .fini:
 11e8 f30f1efa 4883ec08 4883c408 c3        ....H...H....   
Contents of section .rodata:
 2000 01000200 48656c6c 6f2c2077 6f726c64  ....Hello, world
 2010 2100                                 !.              
Contents of section .eh_frame_hdr:
 2014 011b033b 40000000 07000000 0cf0ffff  ...;@...........
 2024 74000000 2cf0ffff 9c000000 3cf0ffff  t...,.......<...
 2034 b4000000 4cf0ffff 5c000000 35f1ffff  ....L...\...5...
 2044 cc000000 5cf1ffff ec000000 ccf1ffff  ....\...........
 2054 34010000                             4...            
Contents of section .eh_frame:
 2058 14000000 00000000 017a5200 01781001  .........zR..x..
 2068 1b0c0708 90010000 14000000 1c000000  ................
 2078 e8efffff 2f000000 00440710 00000000  ..../....D......
 2088 24000000 34000000 90efffff 20000000  $...4....... ...
 2098 000e1046 0e184a0f 0b770880 003f1a3a  ...F..J..w...?.:
 20a8 2a332422 00000000 14000000 5c000000  *3$"........\...
 20b8 88efffff 10000000 00000000 00000000  ................
 20c8 14000000 74000000 80efffff 10000000  ....t...........
 20d8 00000000 00000000 1c000000 8c000000  ................
 20e8 61f0ffff 20000000 00450e10 8602430d  a... ....E....C.
 20f8 06570c07 08000000 44000000 ac000000  .W......D.......
 2108 68f0ffff 65000000 00460e10 8f02490e  h...e....F....I.
 2118 188e0345 0e208d04 450e288c 05440e30  ...E. ..E.(..D.0
 2128 8606480e 38830747 0e406e0e 38410e30  ..H.8..G.@n.8A.0
 2138 410e2842 0e20420e 18420e10 420e0800  A.(B. B..B..B...
 2148 10000000 f4000000 90f0ffff 05000000  ................
 2158 00000000 00000000                    ........        
Contents of section .init_array:
 3db8 40110000 00000000                    @.......        
Contents of section .fini_array:
 3dc0 00110000 00000000                    ........        
Contents of section .dynamic:
 3dc8 01000000 00000000 01000000 00000000  ................
 3dd8 0c000000 00000000 00100000 00000000  ................
 3de8 0d000000 00000000 e8110000 00000000  ................
 3df8 19000000 00000000 b83d0000 00000000  .........=......
 3e08 1b000000 00000000 08000000 00000000  ................
 3e18 1a000000 00000000 c03d0000 00000000  .........=......
 3e28 1c000000 00000000 08000000 00000000  ................
 3e38 f5feff6f 00000000 a0030000 00000000  ...o............
 3e48 05000000 00000000 70040000 00000000  ........p.......
 3e58 06000000 00000000 c8030000 00000000  ................
 3e68 0a000000 00000000 84000000 00000000  ................
 3e78 0b000000 00000000 18000000 00000000  ................
 3e88 15000000 00000000 00000000 00000000  ................
 3e98 03000000 00000000 b83f0000 00000000  .........?......
 3ea8 02000000 00000000 18000000 00000000  ................
 3eb8 14000000 00000000 07000000 00000000  ................
 3ec8 17000000 00000000 e8050000 00000000  ................
 3ed8 07000000 00000000 28050000 00000000  ........(.......
 3ee8 08000000 00000000 c0000000 00000000  ................
 3ef8 09000000 00000000 18000000 00000000  ................
 3f08 1e000000 00000000 08000000 00000000  ................
 3f18 fbffff6f 00000000 01000008 00000000  ...o............
 3f28 feffff6f 00000000 08050000 00000000  ...o............
 3f38 ffffff6f 00000000 01000000 00000000  ...o............
 3f48 f0ffff6f 00000000 f4040000 00000000  ...o............
 3f58 f9ffff6f 00000000 03000000 00000000  ...o............
 3f68 00000000 00000000 00000000 00000000  ................
 3f78 00000000 00000000 00000000 00000000  ................
 3f88 00000000 00000000 00000000 00000000  ................
 3f98 00000000 00000000 00000000 00000000  ................
 3fa8 00000000 00000000 00000000 00000000  ................
Contents of section .got:
 3fb8 c83d0000 00000000 00000000 00000000  .=..............
 3fc8 00000000 00000000 30100000 00000000  ........0.......
 3fd8 00000000 00000000 00000000 00000000  ................
 3fe8 00000000 00000000 00000000 00000000  ................
 3ff8 00000000 00000000                    ........        
Contents of section .data:
 4000 00000000 00000000 08400000 00000000  .........@......
Contents of section .comment:
 0000 4743433a 20285562 756e7475 20392e33  GCC: (Ubuntu 9.3
 0010 2e302d31 37756275 6e747531 7e32302e  .0-17ubuntu1~20.
 0020 30342920 392e332e 3000               04) 9.3.0.      

Disassembly of section .init:

0000000000001000 <_init>:
    1000:	f3 0f 1e fa          	endbr64 
    1004:	48 83 ec 08          	sub    $0x8,%rsp
    1008:	48 8b 05 d9 2f 00 00 	mov    0x2fd9(%rip),%rax        # 3fe8 <__gmon_start__>
    100f:	48 85 c0             	test   %rax,%rax
    1012:	74 02                	je     1016 <_init+0x16>
    1014:	ff d0                	callq  *%rax
    1016:	48 83 c4 08          	add    $0x8,%rsp
    101a:	c3                   	retq   

Disassembly of section .plt:

0000000000001020 <.plt>:
    1020:	ff 35 9a 2f 00 00    	pushq  0x2f9a(%rip)        # 3fc0 <_GLOBAL_OFFSET_TABLE_+0x8>
    1026:	f2 ff 25 9b 2f 00 00 	bnd jmpq *0x2f9b(%rip)        # 3fc8 <_GLOBAL_OFFSET_TABLE_+0x10>
    102d:	0f 1f 00             	nopl   (%rax)
    1030:	f3 0f 1e fa          	endbr64 
    1034:	68 00 00 00 00       	pushq  $0x0
    1039:	f2 e9 e1 ff ff ff    	bnd jmpq 1020 <.plt>
    103f:	90                   	nop

Disassembly of section .plt.got:

0000000000001040 <__cxa_finalize@plt>:
    1040:	f3 0f 1e fa          	endbr64 
    1044:	f2 ff 25 ad 2f 00 00 	bnd jmpq *0x2fad(%rip)        # 3ff8 <__cxa_finalize@GLIBC_2.2.5>
    104b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .plt.sec:

0000000000001050 <printf@plt>:
    1050:	f3 0f 1e fa          	endbr64 
    1054:	f2 ff 25 75 2f 00 00 	bnd jmpq *0x2f75(%rip)        # 3fd0 <printf@GLIBC_2.2.5>
    105b:	0f 1f 44 00 00       	nopl   0x0(%rax,%rax,1)

Disassembly of section .text:

0000000000001060 <_start>:
    1060:	f3 0f 1e fa          	endbr64 
    1064:	31 ed                	xor    %ebp,%ebp
    1066:	49 89 d1             	mov    %rdx,%r9
    1069:	5e                   	pop    %rsi
    106a:	48 89 e2             	mov    %rsp,%rdx
    106d:	48 83 e4 f0          	and    $0xfffffffffffffff0,%rsp
    1071:	50                   	push   %rax
    1072:	54                   	push   %rsp
    1073:	4c 8d 05 66 01 00 00 	lea    0x166(%rip),%r8        # 11e0 <__libc_csu_fini>
    107a:	48 8d 0d ef 00 00 00 	lea    0xef(%rip),%rcx        # 1170 <__libc_csu_init>
    1081:	48 8d 3d c1 00 00 00 	lea    0xc1(%rip),%rdi        # 1149 <main>
    1088:	ff 15 52 2f 00 00    	callq  *0x2f52(%rip)        # 3fe0 <__libc_start_main@GLIBC_2.2.5>
    108e:	f4                   	hlt    
    108f:	90                   	nop

0000000000001090 <deregister_tm_clones>:
    1090:	48 8d 3d 79 2f 00 00 	lea    0x2f79(%rip),%rdi        # 4010 <__TMC_END__>
    1097:	48 8d 05 72 2f 00 00 	lea    0x2f72(%rip),%rax        # 4010 <__TMC_END__>
    109e:	48 39 f8             	cmp    %rdi,%rax
    10a1:	74 15                	je     10b8 <deregister_tm_clones+0x28>
    10a3:	48 8b 05 2e 2f 00 00 	mov    0x2f2e(%rip),%rax        # 3fd8 <_ITM_deregisterTMCloneTable>
    10aa:	48 85 c0             	test   %rax,%rax
    10ad:	74 09                	je     10b8 <deregister_tm_clones+0x28>
    10af:	ff e0                	jmpq   *%rax
    10b1:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    10b8:	c3                   	retq   
    10b9:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

00000000000010c0 <register_tm_clones>:
    10c0:	48 8d 3d 49 2f 00 00 	lea    0x2f49(%rip),%rdi        # 4010 <__TMC_END__>
    10c7:	48 8d 35 42 2f 00 00 	lea    0x2f42(%rip),%rsi        # 4010 <__TMC_END__>
    10ce:	48 29 fe             	sub    %rdi,%rsi
    10d1:	48 89 f0             	mov    %rsi,%rax
    10d4:	48 c1 ee 3f          	shr    $0x3f,%rsi
    10d8:	48 c1 f8 03          	sar    $0x3,%rax
    10dc:	48 01 c6             	add    %rax,%rsi
    10df:	48 d1 fe             	sar    %rsi
    10e2:	74 14                	je     10f8 <register_tm_clones+0x38>
    10e4:	48 8b 05 05 2f 00 00 	mov    0x2f05(%rip),%rax        # 3ff0 <_ITM_registerTMCloneTable>
    10eb:	48 85 c0             	test   %rax,%rax
    10ee:	74 08                	je     10f8 <register_tm_clones+0x38>
    10f0:	ff e0                	jmpq   *%rax
    10f2:	66 0f 1f 44 00 00    	nopw   0x0(%rax,%rax,1)
    10f8:	c3                   	retq   
    10f9:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001100 <__do_global_dtors_aux>:
    1100:	f3 0f 1e fa          	endbr64 
    1104:	80 3d 05 2f 00 00 00 	cmpb   $0x0,0x2f05(%rip)        # 4010 <__TMC_END__>
    110b:	75 2b                	jne    1138 <__do_global_dtors_aux+0x38>
    110d:	55                   	push   %rbp
    110e:	48 83 3d e2 2e 00 00 	cmpq   $0x0,0x2ee2(%rip)        # 3ff8 <__cxa_finalize@GLIBC_2.2.5>
    1115:	00 
    1116:	48 89 e5             	mov    %rsp,%rbp
    1119:	74 0c                	je     1127 <__do_global_dtors_aux+0x27>
    111b:	48 8b 3d e6 2e 00 00 	mov    0x2ee6(%rip),%rdi        # 4008 <__dso_handle>
    1122:	e8 19 ff ff ff       	callq  1040 <__cxa_finalize@plt>
    1127:	e8 64 ff ff ff       	callq  1090 <deregister_tm_clones>
    112c:	c6 05 dd 2e 00 00 01 	movb   $0x1,0x2edd(%rip)        # 4010 <__TMC_END__>
    1133:	5d                   	pop    %rbp
    1134:	c3                   	retq   
    1135:	0f 1f 00             	nopl   (%rax)
    1138:	c3                   	retq   
    1139:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001140 <frame_dummy>:
    1140:	f3 0f 1e fa          	endbr64 
    1144:	e9 77 ff ff ff       	jmpq   10c0 <register_tm_clones>

0000000000001149 <main>:
    1149:	f3 0f 1e fa          	endbr64 
    114d:	55                   	push   %rbp
    114e:	48 89 e5             	mov    %rsp,%rbp
    1151:	48 8d 3d ac 0e 00 00 	lea    0xeac(%rip),%rdi        # 2004 <_IO_stdin_used+0x4>
    1158:	b8 00 00 00 00       	mov    $0x0,%eax
    115d:	e8 ee fe ff ff       	callq  1050 <printf@plt>
    1162:	b8 00 00 00 00       	mov    $0x0,%eax
    1167:	5d                   	pop    %rbp
    1168:	c3                   	retq   
    1169:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)

0000000000001170 <__libc_csu_init>:
    1170:	f3 0f 1e fa          	endbr64 
    1174:	41 57                	push   %r15
    1176:	4c 8d 3d 3b 2c 00 00 	lea    0x2c3b(%rip),%r15        # 3db8 <__frame_dummy_init_array_entry>
    117d:	41 56                	push   %r14
    117f:	49 89 d6             	mov    %rdx,%r14
    1182:	41 55                	push   %r13
    1184:	49 89 f5             	mov    %rsi,%r13
    1187:	41 54                	push   %r12
    1189:	41 89 fc             	mov    %edi,%r12d
    118c:	55                   	push   %rbp
    118d:	48 8d 2d 2c 2c 00 00 	lea    0x2c2c(%rip),%rbp        # 3dc0 <__do_global_dtors_aux_fini_array_entry>
    1194:	53                   	push   %rbx
    1195:	4c 29 fd             	sub    %r15,%rbp
    1198:	48 83 ec 08          	sub    $0x8,%rsp
    119c:	e8 5f fe ff ff       	callq  1000 <_init>
    11a1:	48 c1 fd 03          	sar    $0x3,%rbp
    11a5:	74 1f                	je     11c6 <__libc_csu_init+0x56>
    11a7:	31 db                	xor    %ebx,%ebx
    11a9:	0f 1f 80 00 00 00 00 	nopl   0x0(%rax)
    11b0:	4c 89 f2             	mov    %r14,%rdx
    11b3:	4c 89 ee             	mov    %r13,%rsi
    11b6:	44 89 e7             	mov    %r12d,%edi
    11b9:	41 ff 14 df          	callq  *(%r15,%rbx,8)
    11bd:	48 83 c3 01          	add    $0x1,%rbx
    11c1:	48 39 dd             	cmp    %rbx,%rbp
    11c4:	75 ea                	jne    11b0 <__libc_csu_init+0x40>
    11c6:	48 83 c4 08          	add    $0x8,%rsp
    11ca:	5b                   	pop    %rbx
    11cb:	5d                   	pop    %rbp
    11cc:	41 5c                	pop    %r12
    11ce:	41 5d                	pop    %r13
    11d0:	41 5e                	pop    %r14
    11d2:	41 5f                	pop    %r15
    11d4:	c3                   	retq   
    11d5:	66 66 2e 0f 1f 84 00 	data16 nopw %cs:0x0(%rax,%rax,1)
    11dc:	00 00 00 00 

00000000000011e0 <__libc_csu_fini>:
    11e0:	f3 0f 1e fa          	endbr64 
    11e4:	c3                   	retq   

Disassembly of section .fini:

00000000000011e8 <_fini>:
    11e8:	f3 0f 1e fa          	endbr64 
    11ec:	48 83 ec 08          	sub    $0x8,%rsp
    11f0:	48 83 c4 08          	add    $0x8,%rsp
    11f4:	c3                   	retq   

# Workshop_RTL_Design_SKY130_Technology
A report on 5 day workshop on RTL design and synthesis using opensource tools - iverilog, gtkwave, yosys and sky130-130nm technology PDK and standard cell library.
# Table of contents
 - [Day-1- Introduction to Verilog RTL Design and Synthesis](#1-Introduction-to-Verilog-RTL-Design-and-Synthesis)
    - [1.1 Introduction](#11-Introduction)
    - [1.2 Introduction to iverilog and gtkwave based simulation](#12-Introduction-to-iveriilog-and-gtkwave-based-simulation)
    - [1.3 Introduction to Yosys and Logic Synthesizer](#13-Introduction-to-Yosys-and-Logic-Synthesizer)
  - [Day-2- Timing Libraries, Hierarchical and Flat Synthesis](#2-Timing-Libraries-Hierarchical-and-Flat-Synthesis)
    - [2.1 Introduction to Timing Libraries](#21-Introduction-to-Timing-Libraries)
    - [2.2 Hierarchical Synthesis and Flat Synthesis](#22-Hierarchical-Synthesis-and-Flat-Synthesis)
    - [2.3 Various Flip Flop coding Styles and Optimizations](#23-Various-Flip-Flop-coding-Styles-and-Optimizations)
    - [2.4 Interesting Optimizations](#24-Interesting-Optimizations)
  - [Day-3- Combinational and Sequential Optimization](#3-Combinational-and-Sequential-Optimization)
    - [3.1 Introduction to Optimizations](#31-Introduction-to-Optimizations)
    - [3.2 Combinational Logic Optimizations](#32-Combinational-Logic-Optimizations)
    - [3.3 Sequential Logic Optimizations](#33-Sequential-Logic-Optimizations)
    - [3.4 Sequential Optimization for unused outputs](#34-Sequential-Optimization-for-unused-outputs)
  - [Day-4- GLS, Blocking vs Nonblocking and Synthesis-Simulation Mismatch](#4-GLS-Blocking-vs-Nonblocking-and-Synthesis-Simulation-Mismatch)
    - [4.1 GLS Concepts And Flow](#41-GLS-Concepts-And-Flow)
    - [4.2 Synthesis Simulation Mismatch](#42-Synthesis-Simulation-Mismatch)
    - [4.3 Missing Sensitivity List](#43-Missing-Sensitivity-List)
    - [4.4 Blocking and Nonblocking Statements in Verilog](#44-Blocking-and-Nonblocking-Statements-in-Verilog)
  - [Day-5- If, case, for and for generate](#5-If-case-for-and-for-generate)
    - [5.1 If and Case Construct](#51-If-and-Case-Construct)
    - [5.2 Looping Constructs in Verilog](#52-Looping-Constructs-in-Verilog)
  - [Acknowledgement](#6-Acknowledgment)
 
# 1. Introduction to Verilog RTL Design and Synthesis

## 1.1 Introduction

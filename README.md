# <p align = center><b>001_2_CppHelloWorld_std17<b></p>

## The "Hello, World!" app with checking the output of `std::cout`.

### Requirements:
**Compiler</br> / Build System** | **Standard</br> / Version**
--: | :--
**g++** | v.6.3.0
**MinGW** | v.3.82.90
**C++ Standard** | 2017
**CMake** | v.3.20
<!--**clang** | v.11.0.0 --> <!--"C:\Program Files\LLVM\bin"-->
<!--**g++** | v.6.3.0 -->    <!--"C:\MinGW_Compiler_C-C++\bin"-->

<!-- ### Additional libraries
**Library** | **Version**
--: | :--
SDL2 | v.2.0.16 (stable) -->


## Build the project

> **NOTE**:</br> To download and install the latest version of:</br>
> **CMake** use next link: ([*CMake download*][cmake])</br> 
> **MinGW (g++)** toolchain use ([*MinGW download*][mingw])

## **TIP:** To compile and build the project for **Windows OS**
1. Run the **CommandPrompt** or **PowerShell**:
   * `[Win]+[R]` -> Type: *`cmd`* or *`pwsh`* -> `[Shift]+[Ctrl]+[Enter]` *(to get admin rights)*
2. Use the `cd` command to open the root of the project
### *(For Example:)*
```bash
cd %USERPROFILE%\Downloads\001_2_CppHelloWorld_std17
```
3. To keep the source code clean you should do *"out-of-source"* builds.

```bash
mkdir build
cd build
cmake ..
cmake --build .
```
4. To run the target open `\out` folder *(will be generated by CMake)* and run executable file.

```bash
cd ..\out
HelloWorld.exe
```

## **TIP:** To compile and build the project for **\*nix OS**
1. Run the **Terminal**: `[Ctrl]+[Alt]+[T]`
2. Use the `cd` command to open the root of the project
### *(For Example:)*
```bash
cd $home/001_2_CppHelloWorld_std17
```
3. To keep the source code clean you should do *"out-of-source"* builds.

```bash
mkdir build
cd build
cmake ..
cmake --build .
```
4. To run the target open `/out` folder *(will be generated by CMake)* and run executable file.

```bash
cd ../out
HelloWorld
```

### The result:
![Result][result]

repo URL:
```
https://github.com/yoricsv/001_2_CppHelloWorld_std17.git
```

---

<!--
* [*CMake download*][cmake]
* [*MinGW download*][mingw]
* [Result][result]
-->

[cmake]: https://cmake.org/download
[mingw]: https://www.mingw-w64.org/downloads
[result]: res/img/cpp_helloworld_check_cout.png


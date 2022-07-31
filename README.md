# std-string-to-uint8_t-array
Converts an std::string to an uint8_t array.

This was made for people that want to use MemJect for injecting their dll, encrypting becomes a thing and dumbasses won't do anything.

It converts:
```cpp
std::string bytes = "0x4d, 0x5a, 0x80, 0x00, 0x01, 0x00, 0x00, 0x00, 0x04, 0x00, 0x10, 0x00, 0xff, 0xff";
```
To:
```cpp
uint8_t g_binary[] = { 0x4d, 0x5a, 0x80, 0x00, 0x01, 0x00, 0x00, 0x00, 0x04, 0x00, 0x10, 0x00, 0xff, 0xff };
```

project(libc-gmon)

cmake_minimum_required(VERSION 2.4.0)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c89")

set(gmon_sources gmon.c)

add_darling_object_library(libc-gmon ${gmon_sources})

add_subdirectory(libhipSYCL)

if(COMPILE_SOURCE_TRANSFORMATION_TOOLS)
  add_subdirectory(hipsycl_rewrite_includes)
  add_subdirectory(hipsycl_transform_source)
ENDIF()
add_subdirectory(hipsycl_clang_plugin)

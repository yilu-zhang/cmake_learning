PROJECT (HELLO)
SET(SRC_LIST hello_world.cpp)
MESSAGE(STATUS "This is BINARY dir" ${HELLO_BINARY_DIR})
MESSAGE(STATUS "This is SOURCE dir" ${HELLO_SOURCE_DIR})
#ADD_EXECUTABLE(hello hello_world.cpp)
ADD_EXECUTABLE(hello ${SRC_LIST})

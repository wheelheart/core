load("@rules_cc//cc:defs.bzl", "cc_library")

package(default_visibility = ["//visibility:public"])

cc_library(
    name = "class_factory",
    srcs = ["class_factory.cc"],
    hdrs = ["class_factory.h"],
)

cc_library(
    name = "class_loader_utility",
    srcs = ["class_loader_utility.cc"],
    hdrs = ["class_loader_utility.h"],
    deps = [
        ":class_factory",
        "//cyber/class_loader/shared_library",
        "//cyber/common:log",
    ],
)

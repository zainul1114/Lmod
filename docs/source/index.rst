
Lmod: A New Environment Module System
=====================================

PURPOSE
^^^^^^^

Lmod is a Lua based module system that easily handles the MODULEPATH
Hierarchical problem. Environment Modules provide a convenient way to
dynamically change the users' environment through modulefiles. This
includes easily adding or removing directories to the PATH environment
variable. Modulefiles for Library packages provide environment
variables that specify where the library and header files can be
found.

OVERVIEW
^^^^^^^^

This guide is written to explain what Environment Modules are and why
they are very useful for both users and system administrators. Lmod is
an implementation of Environment Modules, much of what is said here is
true for any environment modules system but there are many features
which are unique to Lmod.

Environment Modules provide a convenient way to dynamically change the
users' environment through modulefiles. This includes easily adding or
removing directories to the PATH environment variable.

A modulefile contains the necessary information to allow a user to run
a particular application or provide access to a particular
library. All of this can be done dynamically without logging out and
back in. Modulefiles for applications modify the user's path to make
access easy. Modulefiles for Library packages provide environment
variables that specify where the library and header files can be
found.

Packages can be loaded and unloaded cleanly through the module
system. All the popular shells are supported: bash, ksh, csh, tcsh,
zsh.  Also available for perl and python.

It is also very easy to switch between different versions of a package
or remove it.

Introduction to Lmod
^^^^^^^^^^^^^^^^^^^^

If you are new to Lmod then please read the User Guide and possibly
the Frequently Asked Questions Guide.   Users who wish to read about
how to have their own personal modules should read the Advanced User Guide.

.. toctree::
   :maxdepth: 1

   010_user
   015_writing_modules
   040_FAQ
   020_advanced

Installing Lmod
^^^^^^^^^^^^^^^

Anyone wishing to install Lmod on a personal computer or for a system
should read the Installation Guide as well as the Transitioning to
Lmod Guide.  The rest of the guides can be read as needed.

.. toctree::
   :maxdepth: 1

   030_installing
   045_transition
   050_lua_modulefiles
   055_module_names
   060_locating
   070_standard_modules
   073_tmod_to_lmod

Advanced Topics
^^^^^^^^^^^^^^^

.. toctree::
   :maxdepth: 1
   
   075_bug_reporting
   077_ref_counting
   080_hierarchy
   090_configuring_lmod
   093_modulerc
   095_tcl2lua
   098_dependent_modules
   100_modulefile_examples
   110_lmod_mpi_parallel_filesystem
   120_shared_home_directories
   125_personal_spider_cache
   130_spider_cache
   135_module_spider
   136_spider
   140_deprecating_modules
   145_properties
   160_debugging_modulefiles
   170_hooks
   185_localization
   190_Integration_of_EasyBuild_and_Lmod
   200_avail_custom
   210_load_storms
   220_tracing
   240_sticky_modules
   250_site_package
   260_sh_to_modulefile
   300_tracking_module_usage
   310_settarg
   320_improving_perf

Topics yet to be written
^^^^^^^^^^^^^^^^^^^^^^^^

#. Optional Software layout, two digit rule
#. Advanced Topics: priority path, .modulerc tricks
#. inherit
#. internal structure of lmod.



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

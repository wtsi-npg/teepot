#
# Copyright (c) 2014 Genome Research Ltd.
# Author: Rob Davies <rmd+github@sanger.ac.uk>
#
# This file is part of teepot.
#
# Teepot is free software: you can redistribute it and/or modify it under
# the terms of the GNU General Public License as published by the Free Software
# Foundation; either version 3 of the License, or (at your option) any later
# version.
# This program is distributed in the hope that it will be useful, but WITHOUT
# ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE. See the GNU General Public License for more
# details.
# You should have received a copy of the GNU General Public License along with
# this program. If not, see <http://www.gnu.org/licenses>

TEST_LOG_DRIVER = env AM_TAP_AWK='$(AWK)' $(SHELL) \
                  $(top_srcdir)/build-aux/tap-driver.sh

TESTS_ENVIRONMENT = top_builddir=$(top_builddir)

EXTRA_DIST = teepot.test

TESTS = teepot.test

check_PROGRAMS = test_tp

test_tp_SOURCES = test_tp.c

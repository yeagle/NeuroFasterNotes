MATLAB Basics
=============
We use MATLAB R2020B, which is preinstalled on the computers. To start it,
start a terminal and use the command:

.. code-block:: bash

  matlab9.9

In the MATLAB Window, you need to add the path for SPM12, which is the SPM
Software, we are using:

.. code-block:: matlab

  addpath('/nic/sw/spm/spm12latest')

Then you can start the spm toolbox:

.. code-block:: matlab

  spm

And the CAT12 toolbox:

.. code-block:: matlab

  cat12

Note that you need to start the fMRI section in the spm toolbox before the
cat12 command, the cat12 command won't work.

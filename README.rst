Mixer+ Module
=============

The Mixer+ module includes a basic three channel mixer as well as an attenuverter with the option to add distortion to the output signal.

3 Channel Mixer
---------------

The 3 channel mixer is designed for a maximum of unit gain per channel. 

* DC coupled inputs
* Inverting and non-inverting outputs
* Simple output level indicator (red LED illuminates when :math:`V_{pp} \gtrapprox 9V`)

Attenuverter with Distortion
----------------------------

The input of the attenuverter is connected internally (normaled) to the non-inverting output of the mixer. The internal connection is broken when an external connection is made. The attenuverter output can be optionally distorted or offset with a DC voltage. 

* Input normaled to the non-inverting output of the mixer and is DC coupled
* Gain from -1 to 1
* Optional back-to-back diode distortion (dirty/clean switch)
* DC offset control adds -6 to +6V DC to output signal

References
----------

#. Moritz Klein, "Designing a 3-channel mixer with diode distortion from scratch", `Youtube <https://www.youtube.com/watch?v=q8tmUgaXrEQ>`_
#. Ray Wilson, "Ultra-Simple Mono Audio Mixer #1", `Music From Outer Space <https://musicfromouterspace.com/analogsynth_new/OLDIESBUTGOODIES/AUDIOMIXER/monomixer.html>`_

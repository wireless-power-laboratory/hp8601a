## The hp8601a generator/sweeper

Repository for research and development with the Hewlett-Packard 8601A Generator/Sweeper with Option 007.

![image](/images/8601a-front.jpg)

The Model 8601A offers good CW characteristics with `+/-`1% of frequency dial accuracy and a wide range of continuously adjustable output power levels accurate to `+/-`1 dB from +13 dBm to -110 dBm. A power output meter is calibrated in both dBm and rms volts into 50 ohms. These features and low RDI leakage mean that receiver sensitivity can be measured. In addition, flatness -- power output verses frequency -- is better than `+/-`0.25 dB over the entire band and `+/-`0.1 dB over any 10-Mhz portion from 1 to 110 MHz. Many other signal generator applications can also be satisfied by the 8601A because of its low noise output--more than 70 dB down in a 1-kHz bandwidth.

A unique AM marker system built into the automatic leveling circuit provides 0.01% frequency identification at 5-MHz intervals. The frequency vernier with `+/-`0.1% of frequency variation and the AUX output signal that's always between 100 kHz and 11 MHz regardless of band allow 2-kHz settability on high band -- 200-Hz on low band -- when used with the [hp5245L](https://github.com/cartheur/hp5245l) electronic counter.

A small amount of modulation is available at the flick of a switch to provide a convenient test situation. For example, discriminator sensitivities to AM and FM can be checked without the use of an external oscillator. 30% AM and 75 kHz deviation FM -- 7.5 kHz on low band -- are provided by an internal 1-kHz oscillator. External AM and full band external FM allow the 8601A to be programmed in both frequency and amplitude.

Option 007 enables the 8601A to be used as a tracking generator by substituting an external signal for the 8601A VTO (internal voltage-tuned oscillator) signal. This capability allows the 8601A to be used with the [8553L](https://github.com/cartheur/hp141s) RF Section of the Spectrum Analyzer to provide displays of log amplitude verses frequency with 70 dB display range for sweep widths from 500 kHz to 100 MHz. To obtain this operation, the `First LO` output is taken directly to an 8601A rear-panel input by removing the shorting cable that is used for normal 8601A operation.

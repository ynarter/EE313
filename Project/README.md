
## Term project: Analog Multiplier
We designed a multiplier circuit that can multiply two sine waves. For this purpose, the circuit uses the Gilbert cell , which is the most commonly used analog multiplier.
 
The circuit consists of three differential amplifiers. For an analog multiplier implemented with a Gilbert cell, the sine wave (essentially the wave that will be multiplied) is added to the base of the bias generator of the differential amplifier. With the sinusoidal wave, the quiescent current of the input transistors, along with the gain and transconductance gm of the amplifier, then changes sinusoidally. With the varying current, which is determined by the second sine wave, the output is the multiplication of these sine waves, which is an AM modulated signal.
 
To bias the transistors so that they all operate in forward active region, a voltage divider network from the power supply is designed with resistors. DC block (coupling) capacitors is another fundamental addition to the circuit, to stop the DC current going into the AC signal generator, also to separate the DC bias voltage and the AC voltages.

Specifications:

• 12V DC power supply.

• Power consumption is less than 200mW, i.e., <10mA total current per supply.

• Input waves are 1kHz and 20kHz sine waves with 0.1mV amplitude.

• The circuit generates its own biasing. The circuit consists of 6 NPN BJTs.

• A double balanced mixing cell is used. 

• Given 1kHz and 20kHz sinewaves the output of the circuit is the multiplication of these
two signals. Please refer to the [report](https://github.com/ynarter/EE313/blob/main/Project/project_report_oznurbulca_yigitnarter.pdf) for results and further implementation details.



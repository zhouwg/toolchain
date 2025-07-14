# Compliance Statement

Currently, Qualcomm's Hexagon SDK can't downloaded automatically via the script [build-run-ggmlhexagon-android.sh](https://github.com/zhouwg/ggml-hexagon/blob/self-build/scripts/build-run-ggmlhexagon-android.sh) because of well-known and make-sense IPR policy. I provide a customized&tailored minimal Hexagon SDK to **simplify workflow** of build ggml-hexagon under the premise of **strictly abiding by Qualcomm's IPR policy.**  At the same time, **I strongly recommend that developers should obtain the fully Hexagon SDK with a valid Qualcomm Developer Account** because this minimal-hexagon-sdk only used for build ggml-hexagon(in other words, **there are only header files and binary programs/libs in this highly-tailored minimal-hexagon-sdk**), that's a fully compliant manner and without any IPR concern/risk.


The official Qualcomm's Hexagon SDK tech docs can be found at: https://docs.qualcomm.com/bundle/publicresource/topics/80-77512-1/hexagon-dsp-sdk-collection-landing-page.html?product=1601111740010422


# Contents in this repo

minimal-hexagon-sdk-6.2.0.1.xz: a customized/tailored Hexagon SDK from Qualcomm's official Hexagon SDK 6.2.0.1, size of this file is about 516M. the purpose of this file is to simplify workflow of build ggml-hexagon.

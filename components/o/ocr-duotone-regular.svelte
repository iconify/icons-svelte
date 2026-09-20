<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5ak1dhxf"/><path class="kw50e_bvi"/><path class="k35wv8y0z"/><path class="eojr-cxjg"/><path class="sqpfjbblj"/><path class="h23_vdqvb"/><path class="dxxnlbcax"/><path class="a71lhwniq"/><path class="a-r3j5f7z"/><path class="xt7079b9x"/><path class="qvytntb8g"/><path class="s13ysjbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocr-duotone-regular" {...props}></Icon>
<style>
:global(.a-r3j5f7z) {
  d: path("M3 16v4h5");
}

:global(.a71lhwniq) {
  d: path("M16 4h5v4");
}

:global(.b5ak1dhxf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8V4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dxxnlbcax) {
  d: path("M3 8V4h5");
}

:global(.eojr-cxjg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 20h5v-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h23_vdqvb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 14h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k35wv8y0z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16v4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kw50e_bvi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvytntb8g) {
  d: path("M7 10h10");
}

:global(.s13ysjbyf) {
  d: path("M7 14h7");
}

:global(.sqpfjbblj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xt7079b9x) {
  d: path("M16 20h5v-4");
}

</style>

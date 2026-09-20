<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="lt2hdfbrw"/><path class="cix0a735a"/><path class="b14occbcx"/><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-note-duotone-thin" {...props}></Icon>
<style>
:global(.b14occbcx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cix0a735a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ew7y79byi) {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f6q7r5bds) {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.huj3g_bus) {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.krwm4ebpd) {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lt2hdfbrw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nycbsrkgh) {
  d: path("M17 17V5");
}

:global(.wwbyt5bkd) {
  d: path("M9 5h8");
}

:global(.xob7qnbfo) {
  d: path("M9 17V5");
}

</style>

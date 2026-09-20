<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtfcgd5bf"/><path class="swwpttflz"/><path class="a8b_i2bss"/><path class="f22ajzb8t"/><path class="vhnbtvbtn"/><path class="x1w930bwh"/><path class="a_-b16kjh"/><path class="yih0nfb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coach-duotone-thin" {...props}></Icon>
<style>
:global(.a_-b16kjh) {
  d: path("M15 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.a8b_i2bss) {
  fill: currentColor;
  d: path("M15 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f22ajzb8t) {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.swwpttflz) {
  fill: currentColor;
  d: path("M5 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.vtfcgd5bf) {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x1w930bwh) {
  d: path("M5 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzsthfbrb"/><path class="xlm4t5bbx"/><path class="nzpsuduik"/><path class="f8gsx7b5s"/><path class="vslz5yb3q"/><path class="rynjb5q0q"/><path class="h33iclbph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-sheet-duotone-thin" {...props}></Icon>
<style>
:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.h33iclbph) {
  d: path("M11 16V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzsthfbrb) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.rynjb5q0q) {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vslz5yb3q) {
  d: path("M6 12h12");
}

:global(.xlm4t5bbx) {
  fill: currentColor;
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

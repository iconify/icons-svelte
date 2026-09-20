<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k5x2esuhl"/><path class="fi3uhubah"/><path class="jdo7z8-qu"/><path class="w-bnpitut"/><path class="ws24-9bwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paintbrush-duotone-thin" {...props}></Icon>
<style>
:global(.fi3uhubah) {
  fill: currentColor;
  d: path("m19 13 2 -2 -4 -4 -2 2Z");
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

:global(.jdo7z8-qu) {
  d: path("m3 21 9 -9");
}

:global(.k5x2esuhl) {
  fill: currentColor;
  d: path("m12 12 3 -3 4 4 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w-bnpitut) {
  d: path("m12 12 3 -3 4 4 -3 3Z");
}

:global(.ws24-9bwu) {
  d: path("m19 13 2 -2 -4 -4 -2 2Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwtupfbyx"/><path class="dps_k9bgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:discoloured-water" {...props}></Icon>
<style>
:global(.dps_k9bgq) {
  fill: currentColor;
  d: path("M10 17a4.5 4.5 0 0 0 9 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwtupfbyx) {
  d: path("M4 3h8a4 4 0 0 1 4 4v1.5h-3V7a1 1 0 0 0-1-1H4Zm10.5 8.5C16.5 14 19 16 19 17a4.5 4.5 0 0 1-9 0c0-1 2.5-3 4.5-5.5");
}

</style>

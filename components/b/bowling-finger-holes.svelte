<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwocv2o6o"/><path class="kt40boc5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bowling-finger-holes" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kt40boc5x) {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5.5-4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.kwocv2o6o) {
  d: path("M3 21.5A18.5 18.5 0 0 1 21.5 3");
}

</style>

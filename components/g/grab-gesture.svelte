<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msjx54bzl"/><path class="yp_o9fi9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grab-gesture" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.msjx54bzl) {
  d: path("M5.25 6.5a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0a1.75 1.75 0 0 1 3.5 0v7c0 4-2.5 6.5-6.5 6.5h-1c-4 0-6.5-2.5-6.5-6.5Z");
}

:global(.yp_o9fi9d) {
  d: path("M5.25 11h7a1.75 1.75 0 0 1 0 3.5h-3.5m0-8v1.75m3.5-1.75v1.75m3.5-1.75v1.75");
}

</style>

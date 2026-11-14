<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uw0qvqr_x"/><path class="iywm0tbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carbon-budget" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iywm0tbau) {
  d: path("M13.5 13.5v8a8 8 0 0 0 8-8Z");
}

:global(.uw0qvqr_x) {
  d: path("M10.5 10.5h8a8 8 0 1 0-8 8Z");
}

</style>

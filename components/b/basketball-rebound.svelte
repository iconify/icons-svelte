<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oms6bhckd"/><path class="k4imskycm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:basketball-rebound" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4imskycm) {
  d: path("M4.75 13.25q3.25 3.25 0 6.5m6.5-6.5q-3.25 3.25 0 6.5");
}

:global(.oms6bhckd) {
  d: path("M20.5 3v11M3 3.5l15 4l-5 2.5m-9.5 6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0 0h9");
}

</style>

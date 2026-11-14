<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwa14racn"/><path class="appg_y4mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-range-slider" {...props}></Icon>
<style>
:global(.appg_y4mg) {
  fill: currentColor;
  d: path("M11 10.75h2A1.25 1.25 0 0 1 14.25 12A1.25 1.25 0 0 1 13 13.25h-2A1.25 1.25 0 0 1 9.75 12A1.25 1.25 0 0 1 11 10.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pwa14racn) {
  d: path("M4.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m10 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M2.5 12h1.75m15.5 0h1.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4scshb7d"/><path class="jynfe_b8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gantry-robot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jynfe_b8p) {
  d: path("M11 4h2a1.5 1.5 0 0 1 1.5 1.5V6A1.5 1.5 0 0 1 13 7.5h-2A1.5 1.5 0 0 1 9.5 6v-.5A1.5 1.5 0 0 1 11 4m1 3.5v5m-3 4v-4h6v4");
}

:global(.m4scshb7d) {
  d: path("M4 21V4h16v17");
}

</style>

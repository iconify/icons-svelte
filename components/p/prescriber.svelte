<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ly5wdeb5f"/><path class="qy4vwactw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:prescriber" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ly5wdeb5f) {
  d: path("M12.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.86 0 1.679.092 2.438.266M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10.25 8h2a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-2A1.75 1.75 0 0 1 15 19.75v-3A1.75 1.75 0 0 1 16.75 15");
}

:global(.qy4vwactw) {
  d: path("M17.25 14h1a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

</style>

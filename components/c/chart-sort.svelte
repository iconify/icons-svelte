<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="caed3i82z"/><path class="kwv8ry9mg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-sort" {...props}></Icon>
<style>
:global(.caed3i82z) {
  d: path("M3.5 3v17.5h9.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kwv8ry9mg) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-3 17v-7m-1.75 1.75L16 14.5l1.75 1.75M20 14.5v7m-1.75-1.75L20 21.5l1.75-1.75");
}

</style>

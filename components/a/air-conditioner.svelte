<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q7ukifgja"/><path class="puoz56gnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-conditioner" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.puoz56gnk) {
  d: path("M6.25 10h11.5M7.5 16.25c0 1.5-1 2-1 3.5m5.5-3.5v4.5m4.5-4.5c0 1.5 1 2 1 3.5");
}

:global(.q7ukifgja) {
  width: 18.5px;
  height: 8.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>

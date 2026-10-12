<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwc02jhmg"/><path class="s1yv7xbwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:panorama" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwc02jhmg) {
  d: path("M2.75 8.25a1 1 0 0 1 1.3-.95q7.95 2.4 15.9 0a1 1 0 0 1 1.3.95v7.5a1 1 0 0 1-1.3.95q-7.95-2.4-15.9 0a1 1 0 0 1-1.3-.95Z");
}

:global(.s1yv7xbwz) {
  d: path("m7 14.5l3-3l2.25 2.25L14 12l2.75 2.75");
}

</style>

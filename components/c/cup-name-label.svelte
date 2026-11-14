<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ln0eq99ll"/><path class="b01zpc03g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cup-name-label" {...props}></Icon>
<style>
:global(.b01zpc03g) {
  d: path("M10.75 10h2.5A1.75 1.75 0 0 1 15 11.75v1.5A1.75 1.75 0 0 1 13.25 15h-2.5A1.75 1.75 0 0 1 9 13.25v-1.5A1.75 1.75 0 0 1 10.75 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ln0eq99ll) {
  d: path("M5.75 3h12.5A1.75 1.75 0 0 1 20 4.75a1.75 1.75 0 0 1-1.75 1.75H5.75A1.75 1.75 0 0 1 4 4.75A1.75 1.75 0 0 1 5.75 3M5 6.5L7 21h10l2-14.5");
}

</style>

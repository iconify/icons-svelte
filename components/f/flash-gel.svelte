<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4pn_bb4n"/><path class="tyznh7bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flash-gel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m4pn_bb4n) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v4a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 10.5v-4A3.5 3.5 0 0 1 6.5 3m3.75 11h3.5a1.75 1.75 0 0 1 1.75 1.75v4a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 10.25 14");
}

:global(.tyznh7bhz) {
  d: path("M8 6h8a1.5 1.5 0 0 1 1.5 1.5v2A1.5 1.5 0 0 1 16 11H8a1.5 1.5 0 0 1-1.5-1.5v-2A1.5 1.5 0 0 1 8 6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4bw5qtpe"/><path class="q-nvjubxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:feed-refresh" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q-nvjubxi) {
  d: path("M10.25 2.25L12 4l-1.75 1.75m.375 2.75h2.75A2.625 2.625 0 0 1 16 11.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 8 13.875v-2.75A2.625 2.625 0 0 1 10.625 8.5m.125 4h2.5");
}

:global(.z4bw5qtpe) {
  d: path("M20.5 12.5A8.5 8.5 0 1 1 12 4");
}

</style>

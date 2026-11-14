<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xy-oaab2i"/><path class="is9yw-ydv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:archimedes" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is9yw-ydv) {
  d: path("M10.75 7h2.5A1.75 1.75 0 0 1 15 8.75v4.5A1.75 1.75 0 0 1 13.25 15h-2.5A1.75 1.75 0 0 1 9 13.25v-4.5A1.75 1.75 0 0 1 10.75 7M4 10h5m6 0h5");
}

:global(.xy-oaab2i) {
  d: path("M4 4v15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V4");
}

</style>

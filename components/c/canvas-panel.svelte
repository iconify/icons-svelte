<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wq-oonbmx"/><path class="dx6fnabvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:canvas-panel" {...props}></Icon>
<style>
:global(.dx6fnabvp) {
  d: path("M8 6h8a1.5 1.5 0 0 1 1.5 1.5v9A1.5 1.5 0 0 1 16 18H8a1.5 1.5 0 0 1-1.5-1.5v-9A1.5 1.5 0 0 1 8 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wq-oonbmx) {
  d: path("M5.25 3h13.5a1.75 1.75 0 0 1 1.75 1.75v14.5A1.75 1.75 0 0 1 18.75 21H5.25a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 5.25 3");
}

</style>

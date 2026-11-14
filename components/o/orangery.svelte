<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msjgnjbvn"/><path class="rmdq3e2nz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:orangery" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.msjgnjbvn) {
  d: path("M3 19.5v-8.733a1.5 1.5 0 0 1 .622-1.216l7.5-5.417a1.5 1.5 0 0 1 1.756 0l7.5 5.417A1.5 1.5 0 0 1 21 10.767V19.5a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5M3 10h18m-9-6.5V10m-5.5 0v11m11-11v11");
}

:global(.rmdq3e2nz) {
  d: path("M9.25 16a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>

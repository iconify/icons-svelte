<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i5k0ytb0x"/><path class="am_jncbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-bay-compact" {...props}></Icon>
<style>
:global(.am_jncbum) {
  d: path("M7.5 16.5v-4l1.5-4h6l1.5 4v4Zm0-4h9m-7.5 4v2m6-2v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5k0ytb0x) {
  d: path("M3 2.5v19h18v-19");
}

</style>

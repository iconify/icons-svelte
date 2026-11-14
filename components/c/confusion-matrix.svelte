<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-d70zb3t"/><path class="pyugfmblk"/><path class="ai1yo_bjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:confusion-matrix" {...props}></Icon>
<style>
:global(.ai1yo_bjj) {
  fill: currentColor;
  d: path("M16.125 13.5h1.25A2.625 2.625 0 0 1 20 16.125v1.25A2.625 2.625 0 0 1 17.375 20h-1.25a2.625 2.625 0 0 1-2.625-2.625v-1.25a2.625 2.625 0 0 1 2.625-2.625");
}

:global(.b-d70zb3t) {
  fill: currentColor;
  d: path("M6.625 4h1.25A2.625 2.625 0 0 1 10.5 6.625v1.25A2.625 2.625 0 0 1 7.875 10.5h-1.25A2.625 2.625 0 0 1 4 7.875v-1.25A2.625 2.625 0 0 1 6.625 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pyugfmblk) {
  d: path("M16.125 4h1.25A2.625 2.625 0 0 1 20 6.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-1.25A2.625 2.625 0 0 1 13.5 7.875v-1.25A2.625 2.625 0 0 1 16.125 4m-9.5 9.5h1.25a2.625 2.625 0 0 1 2.625 2.625v1.25A2.625 2.625 0 0 1 7.875 20h-1.25A2.625 2.625 0 0 1 4 17.375v-1.25A2.625 2.625 0 0 1 6.625 13.5");
}

</style>

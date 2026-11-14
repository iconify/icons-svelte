<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pcd-iubru"/><path class="fu4xlab4u"/><path class="ha8prubvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-field" {...props}></Icon>
<style>
:global(.fu4xlab4u) {
  fill: currentColor;
  d: path("M4.25 3.5h5A1.75 1.75 0 0 1 11 5.25A1.75 1.75 0 0 1 9.25 7h-5A1.75 1.75 0 0 1 2.5 5.25A1.75 1.75 0 0 1 4.25 3.5");
}

:global(.ha8prubvr) {
  d: path("M6.5 13v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pcd-iubru) {
  d: path("M6 10h12a3.5 3.5 0 0 1 3.5 3.5v3A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-3A3.5 3.5 0 0 1 6 10");
}

</style>

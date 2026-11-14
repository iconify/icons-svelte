<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ha9xtnb5j"/><path class="koea7bc5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mirror-round" {...props}></Icon>
<style>
:global(.ha9xtnb5j) {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.koea7bc5n) {
  d: path("m7.25 6.5l4.75-4l4.75 4M7 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0m3.5 0l2-2");
}

</style>

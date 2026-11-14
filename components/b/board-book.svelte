<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qbe76hz4i"/><path class="iem6hdfnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:board-book" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iem6hdfnx) {
  d: path("M4.5 18A3.5 3.5 0 0 1 8 14.5h12M8 2.5v12M9.5 18H17");
}

:global(.qbe76hz4i) {
  d: path("M4.5 18V6A3.5 3.5 0 0 1 8 2.5h9.5A2.5 2.5 0 0 1 20 5v14a2.5 2.5 0 0 1-2.5 2.5H8A3.5 3.5 0 0 1 4.5 18");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-l7suibk"/><path class="zsomxbcxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chemical-suit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-l7suibk) {
  d: path("M7.5 10V7.5a4.5 4.5 0 0 1 9 0v14H13v-5h-2v5H7.5Zm0 1L4 17m-1.25-.75l2.5 1.5M16.5 11l3.5 6m1.25-.75l-2.5 1.5");
}

:global(.zsomxbcxw) {
  d: path("M10 7.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>

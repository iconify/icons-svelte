<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-uoxcbvo"/><path class="zdz-k04xc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cardio-zone" {...props}></Icon>
<style>
:global(.a-uoxcbvo) {
  d: path("m12 20l-7.75-8C2 9.5 2.5 4.5 7 4c2.5-.25 4 1.25 5 2.5c1-1.25 2.5-2.75 5-2.5c4.5.5 5 5.5 2.75 8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdz-k04xc) {
  d: path("M4.25 12H8l1.75-3l2.75 6l1.75-4.5L15.5 12h4.25");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iml9c5bhw"/><path class="gehpesouz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beeswax-wrap" {...props}></Icon>
<style>
:global(.gehpesouz) {
  d: path("M16.5 4.5V7H19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iml9c5bhw) {
  d: path("m3.5 13l2-8.5h11L19 7l1.5 6ZM5 13c0 4 3 6.5 7 6.5s7-2.5 7-6.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0ywq7jsc"/><path class="izj6_nbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gaff-hook" {...props}></Icon>
<style>
:global(.g0ywq7jsc) {
  d: path("m4 20.5l7-12.25c1.5-2.75 5-4.75 7-2.75C19.5 7 19 10 17 11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izj6_nbum) {
  d: path("M17 11c3 2 3 5 0 7l2 3h-4l2-3c-3-2-3-5 0-7");
}

</style>

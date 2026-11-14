<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npr9l7b2y"/><path class="x2ho6y6-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chew-toy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.npr9l7b2y) {
  d: path("M20 12a5 5 0 0 1-4 7a5 5 0 0 1-8 0a5 5 0 0 1-4-7a5 5 0 0 1 4-7a5 5 0 0 1 8 0a5 5 0 0 1 4 7");
}

:global(.x2ho6y6-n) {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>

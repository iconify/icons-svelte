<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="af5l-sn9e"/><path class="m1csnre9n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:creamer-cup" {...props}></Icon>
<style>
:global(.af5l-sn9e) {
  d: path("M4 8a8 2.25 0 1 0 16 0A8 2.25 0 1 0 4 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1csnre9n) {
  d: path("m4 8l2.75 13h10.5L20 8M7.5 6.25l-2-3.75h3l2 3.25");
}

</style>

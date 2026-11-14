<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flrj1hu_m"/><path class="ng6czxbrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-snacks" {...props}></Icon>
<style>
:global(.flrj1hu_m) {
  d: path("m4.5 4.5l1.5-2l1.5 2l1.5-2l1.5 2l1.5-2l1.5 2l1.5-2l1.5 2l1.5-2l1.5 2c2 4.5 2 10.5 0 15l-1.5 2l-1.5-2l-1.5 2l-1.5-2l-1.5 2l-1.5-2l-1.5 2l-1.5-2l-1.5 2l-1.5-2c-2-4.5-2-10.5 0-15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ng6czxbrf) {
  d: path("M7.5 12a4.5 3 0 1 0 9 0a4.5 3 0 1 0-9 0");
}

</style>

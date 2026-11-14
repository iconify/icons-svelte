<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld60hf-ln"/><path class="zdvyzobpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:foot-bath" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ld60hf-ln) {
  d: path("M3 13h18l-1.5 6.5a2 2 0 0 1-2 1.5h-11a2 2 0 0 1-2-1.5ZM7.5 2.5V13m4-10.5v6L15 9.75c1.75.75 2.5 1.75 2.5 3.25");
}

:global(.zdvyzobpc) {
  d: path("M7.5 16.75q1.5-1 3 0m3 0q1.5-1 3 0");
}

</style>

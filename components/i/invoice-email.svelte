<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zge5gfbmi"/><path class="qo-c9xb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:invoice-email" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qo-c9xb-x) {
  d: path("m3 11l9 5.5l9-5.5M9.5 6.5H14");
}

:global(.zge5gfbmi) {
  d: path("M6 10h12a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18v-4.5A3.5 3.5 0 0 1 6 10m.5 0V3.5l1.75-1l1.75 1l1.75-1l1.75 1l1.75-1l1.75 1V10");
}

</style>

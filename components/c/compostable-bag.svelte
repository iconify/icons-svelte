<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aw55qpvbt"/><path class="yf-lz4bnv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compostable-bag" {...props}></Icon>
<style>
:global(.aw55qpvbt) {
  d: path("M6 21.5h12a2 2 0 0 0 2-2c0-5.5-4-8.5-6.5-10l2.5-5l-4 2l-4-2l2.5 5C8 11 4 14 4 19.5a2 2 0 0 0 2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yf-lz4bnv) {
  d: path("M9.5 18.5c0-3 2-4.75 5-4.75c0 2.75-2 4.75-5 4.75m0 0l3-2.75");
}

</style>

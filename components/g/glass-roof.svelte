<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i7wiwtbvv"/><path class="i46sb_buq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:glass-roof" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i46sb_buq) {
  d: path("M2.5 13v6h15v-6m-6-8l-4 8m9-8l-4 8m-8-4h15");
}

:global(.i7wiwtbvv) {
  d: path("m3.585 10.829l2.5-5A1.5 1.5 0 0 1 7.427 5h11.646a1.5 1.5 0 0 1 1.342 2.171l-2.5 5a1.5 1.5 0 0 1-1.342.829H4.927a1.5 1.5 0 0 1-1.342-2.171");
}

</style>

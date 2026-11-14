<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gydtbsbqv"/><path class="zwy5eobsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:panorama" {...props}></Icon>
<style>
:global(.gydtbsbqv) {
  d: path("M2.5 6c6 2 13 2 19 0v12c-6-2-13-2-19 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zwy5eobsu) {
  d: path("m7 14.5l3-3l2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>

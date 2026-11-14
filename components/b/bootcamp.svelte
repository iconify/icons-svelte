<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yacej0bvt"/><path class="pan3f_chh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bootcamp" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pan3f_chh) {
  d: path("M5.5 11.5c-3-5.5-.5-9 4-9S15.5 6 13 10");
}

:global(.yacej0bvt) {
  d: path("M9 10h11.5v5H14a5 5 0 1 1-5-5");
}

</style>

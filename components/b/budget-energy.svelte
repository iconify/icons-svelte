<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yz_2k2d_s"/><path class="hrqunj3_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:budget-energy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrqunj3_f) {
  d: path("m13 10l-2.5 4.25h3L11 18.5");
}

:global(.yz_2k2d_s) {
  d: path("M4.25 18.5a9 9 0 1 1 15.5 0m-3.5-8.75l2-2");
}

</style>

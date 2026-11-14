<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r5659k6od"/><path class="ha4t_hbkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cloning" {...props}></Icon>
<style>
:global(.ha4t_hbkr) {
  fill: currentColor;
  d: path("M10 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r5659k6od) {
  d: path("M2.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>

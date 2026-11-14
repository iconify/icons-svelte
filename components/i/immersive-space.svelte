<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bx8rpubcn"/><path class="yttr8mkjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:immersive-space" {...props}></Icon>
<style>
:global(.bx8rpubcn) {
  d: path("M4.75 18a9.5 9.5 0 1 1 14.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yttr8mkjg) {
  d: path("M4.75 18a7.25 2.5 0 1 0 14.5 0a7.25 2.5 0 1 0-14.5 0");
}

</style>

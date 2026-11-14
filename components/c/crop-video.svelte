<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8jpdz29o"/><path class="x-gjt5bac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crop-video" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k8jpdz29o) {
  d: path("M8.625 6.5h6.75A2.625 2.625 0 0 1 18 9.125v5.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 6 14.875v-5.75A2.625 2.625 0 0 1 8.625 6.5M2.5 7.5v-4h4m11 0h4v4m0 9v4h-4m-11 0h-4v-4");
}

:global(.x-gjt5bac) {
  d: path("m12.25 10.75l.041.029a1.5 1.5 0 0 1 0 2.442l-.041.029a1.107 1.107 0 0 1-1.75-.901v-.698a1.107 1.107 0 0 1 1.75-.901");
}

</style>

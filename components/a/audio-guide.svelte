<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ukg0kpkum"/><path class="lyiugkbct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-guide" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lyiugkbct) {
  d: path("M5.75 12.5zA2.25 2.25 0 0 1 8 14.75v2.5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-2.5a2.25 2.25 0 0 1 2.25-2.25m12.5 0za2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 1-2.25 2.25A2.25 2.25 0 0 1 16 17.25v-2.5a2.25 2.25 0 0 1 2.25-2.25");
}

:global(.ukg0kpkum) {
  d: path("M4.5 13v-1a7.5 7.5 0 0 1 15 0v1");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mcdmdujpa"/><path class="ld4r858hn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-cursing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ld4r858hn) {
  d: path("m7.5 17.5l2.25-2l2.25 2l2.25-2l2.25 2");
}

:global(.mcdmdujpa) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m4.25-4.25l3.5 1.5m7-1.5l-3.5 1.5M9 12h.01M15 12h.01");
}

</style>

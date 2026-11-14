<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsq5xgbnw"/><path class="uv-03jbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:business-home-office" {...props}></Icon>
<style>
:global(.bsq5xgbnw) {
  d: path("M3.5 21V10L12 2.5l8.5 7.5v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uv-03jbid) {
  d: path("M9.75 9.5h4.5A1.75 1.75 0 0 1 16 11.25v2A1.75 1.75 0 0 1 14.25 15h-4.5A1.75 1.75 0 0 1 8 13.25v-2A1.75 1.75 0 0 1 9.75 9.5M12 15v3m-5.75 0h11.5");
}

</style>

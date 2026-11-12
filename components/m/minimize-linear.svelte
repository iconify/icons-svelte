<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vwp374b1w"/><path class="bvt-woblq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-linear" {...props}></Icon>
<style>
:global(.bvt-woblq) {
  d: path("M22 2L15 9M15 3.14286V9H20.8571");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vwp374b1w) {
  d: path("M2 22L9 15M9 20.8571V15H3.14286");
}

</style>

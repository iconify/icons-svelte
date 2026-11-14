<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frjnuhbxx"/><path class="cig4a7bcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:locomotive-front" {...props}></Icon>
<style>
:global(.cig4a7bcq) {
  d: path("M9.25 6.5h5.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 7.5 8.75v-.5A1.75 1.75 0 0 1 9.25 6.5m1 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8 19.5l-2 2m10-2l2 2");
}

:global(.frjnuhbxx) {
  d: path("M4.5 19.5v-11a5 5 0 0 1 5-5h5a5 5 0 0 1 5 5v11Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

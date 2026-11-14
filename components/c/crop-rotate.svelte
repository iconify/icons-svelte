<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yt1rkhbrg"/><path class="vcz-kcbce"/><path class="c3jyl9b_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crop-rotate" {...props}></Icon>
<style>
:global(.c3jyl9b_j) {
  d: path("m17.5 9l2 2l1.75-2.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vcz-kcbce) {
  d: path("M3.5 8.5H15V20M11 2.5a8.5 8.5 0 0 1 8.5 8.5");
}

:global(.yt1rkhbrg) {
  d: path("M6.5 5.5V16H18");
}

</style>

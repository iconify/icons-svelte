<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r49ernf5s"/><circle class="upu83lbfh"/><path class="gkuwju8jy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:allowlist" {...props}></Icon>
<style>
:global(.gkuwju8jy) {
  d: path("m15 17l1.5 1.5l2.75-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r49ernf5s) {
  d: path("M2.75 4.5h18.5m-18.5 5h18.5m-18.5 5h6.5m-6.5 5h6.5");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

</style>

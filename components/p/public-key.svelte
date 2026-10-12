<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="khkxatp1j"/><path class="h_5cn_cef"/><circle class="y5ms0ksxq"/><path class="v7_sv6f-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:public-key" {...props}></Icon>
<style>
:global(.h_5cn_cef) {
  d: path("M9.75 8.5h11.5M15.5 2.75c-2 2-2 9.5 0 11.5c2-2 2-9.5 0-11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.khkxatp1j) {
  cx: 15.5px;
  cy: 8.5px;
  r: 5.75px;
}

:global(.v7_sv6f-i) {
  d: path("M10.25 17.5h11m-2.25 0v2.75m-2.75-2.75v2");
}

:global(.y5ms0ksxq) {
  cx: 6.5px;
  cy: 17.5px;
  r: 3.75px;
}

</style>

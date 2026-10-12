<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="on2kf3b8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:currency-lari" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.on2kf3b8y) {
  d: path("M16 13.5a4 4 0 1 1-5.69-3.63M7.25 17.5H16M10.5 5.75v7m3-7v7");
}

</style>

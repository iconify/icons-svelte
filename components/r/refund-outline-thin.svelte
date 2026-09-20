<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="z7yjp67_f"/><path class="q4bb_8bsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:refund-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ji-xh3b0v) {
  d: path("M8 10.5v3");
}

:global(.lh7nxd5dq) {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.q4bb_8bsv) {
  d: path("M21.5 9.5 19 12l2.5 2.5");
}

:global(.z7yjp67_f) {
  d: path("M18 9.5 15.5 12l2.5 2.5");
}

</style>

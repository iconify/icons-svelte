<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f9xu_cb8q"/><circle class="duo-1eb2o"/><circle class="tbkljbcex"/><path class="kjhqaea1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:git-branch-plus" {...props}></Icon>
<style>
:global(.duo-1eb2o) {
  cx: 6.5px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.f9xu_cb8q) {
  cx: 6.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kjhqaea1x) {
  d: path("M6.5 7.5v9m11-7.5v1.25a3.5 3.5 0 0 1-3.5 3.5h-4a3.5 3.5 0 0 0-3.5 3");
}

:global(.tbkljbcex) {
  cx: 17.5px;
  cy: 6.75px;
  r: 2.25px;
}

</style>

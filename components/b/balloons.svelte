<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="eumxs70ky"/><circle class="w3k3zt4wy"/><circle class="ckdeowbwc"/><path class="orvilebhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:balloons" {...props}></Icon>
<style>
:global(.ckdeowbwc) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
}

:global(.eumxs70ky) {
  cx: 6px;
  cy: 12.75px;
  r: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.orvilebhc) {
  d: path("m6 15.75l6 5.5m6-5.5l-6 5.5m0-12v12");
}

:global(.w3k3zt4wy) {
  cx: 18px;
  cy: 12.75px;
  r: 3px;
}

</style>

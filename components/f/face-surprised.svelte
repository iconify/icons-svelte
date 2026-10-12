<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><circle class="rp30yac0h"/><circle class="kz9_6bmgb"/><path class="kn2vr8bxq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-surprised" {...props}></Icon>
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

:global(.kn2vr8bxq) {
  d: path("M12 13a1.75 2.75 0 1 1 0 5.5a1.75 2.75 0 1 1 0-5.5");
}

:global(.kz9_6bmgb) {
  cx: 15.25px;
  cy: 9.25px;
  r: 2.25px;
}

:global(.rp30yac0h) {
  cx: 8.75px;
  cy: 9.25px;
  r: 2.25px;
}

</style>

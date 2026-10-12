<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dcgw77bis"/><path class="wtqr83b4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:milky-way" {...props}></Icon>
<style>
:global(.dcgw77bis) {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wtqr83b4v) {
  d: path("M12 7.5c3.5 0 5.5 2.5 5.5 5.5S15 20 9 20m3-3.5c-3.5 0-5.5-2.5-5.5-5.5S9 4 15 4");
}

</style>

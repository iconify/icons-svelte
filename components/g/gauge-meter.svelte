<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byxlqys3u"/><path class="s8tk7gw-f"/><circle class="vtw09psrf"/><path class="nz62cmbrj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gauge-meter" {...props}></Icon>
<style>
:global(.byxlqys3u) {
  d: path("M2.75 16.25a9.25 9.25 0 0 1 18.5 0v2.25a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nz62cmbrj) {
  d: path("m12.86 15.02l1.58-2.25");
}

:global(.s8tk7gw-f) {
  d: path("M5.25 16.25a6.75 6.75 0 0 1 13.5 0");
}

:global(.vtw09psrf) {
  cx: 12px;
  cy: 16.25px;
  r: 1.5px;
}

</style>

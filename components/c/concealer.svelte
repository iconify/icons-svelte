<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dvjiwn4hc"/><path class="w5wmovngr"/><rect class="j85p2ubxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:concealer" {...props}></Icon>
<style>
:global(.dvjiwn4hc) {
  width: 6.5px;
  height: 13.75px;
  x: 4.5px;
  y: 7.5px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j85p2ubxc) {
  width: 4.5px;
  height: 10px;
  x: 14px;
  y: 11.25px;
  rx: 1.25px;
}

:global(.w5wmovngr) {
  d: path("M4.5 11H11m5.25-8.25C17.35 4 17.9 4.85 17.9 5.6a1.65 1.65 0 0 1-3.3 0c0-.75.55-1.6 1.65-2.85m0 6.25v2.25");
}

</style>

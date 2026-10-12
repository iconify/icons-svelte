<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frx-4mt8o"/><rect class="qi7kz6b9y"/><path class="ox16jp7cs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pickup-point" {...props}></Icon>
<style>
:global(.frx-4mt8o) {
  d: path("M12 2.75a7.5 7.5 0 0 1 7.5 7.5c0 6.05-7.5 11-7.5 11s-7.5-4.95-7.5-11a7.5 7.5 0 0 1 7.5-7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ox16jp7cs) {
  d: path("M12 7.25V9");
}

:global(.qi7kz6b9y) {
  width: 6px;
  height: 5.5px;
  x: 9px;
  y: 7.25px;
  rx: 0.75px;
}

</style>

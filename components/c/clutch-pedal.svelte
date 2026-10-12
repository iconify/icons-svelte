<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hjru5mbwv"/><path class="j7cd81u7m"/><rect class="tzh58prgc"/><path class="czd18bbiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clutch-pedal" {...props}></Icon>
<style>
:global(.czd18bbiq) {
  d: path("M13.75 13.75h-1.5a2.25 2.25 0 0 0 0 4.5h1.5");
}

:global(.hjru5mbwv) {
  cx: 12px;
  cy: 4px;
  r: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7cd81u7m) {
  d: path("M12 5.25v5.5");
}

:global(.tzh58prgc) {
  width: 11px;
  height: 10.5px;
  x: 6.5px;
  y: 10.75px;
  rx: 2.5px;
}

</style>

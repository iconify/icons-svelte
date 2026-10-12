<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="obz7kdb6f"/><path class="jgyfg-bpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:content-warning" {...props}></Icon>
<style>
:global(.aqmj_4big) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.jgyfg-bpu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.75h.01");
}

:global(.obz7kdb6f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.59 7.6l4.32 8.05q.59 1.1-.66 1.1h-8.5q-1.25 0-.66-1.1l4.32-8.05q.59-1.1 1.18 0M12 10.25v2.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

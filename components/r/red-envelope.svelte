<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="roks055zn"/><path class="j-qrtmxgs"/><path class="e8hdfoncf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:red-envelope" {...props}></Icon>
<style>
:global(.e8hdfoncf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15h.01");
}

:global(.j-qrtmxgs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 7l6 4l6-4");
}

:global(.roks055zn) {
  width: 12px;
  height: 18px;
  x: 6px;
  y: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

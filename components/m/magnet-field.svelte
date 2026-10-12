<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mfxvsbbqy"/><rect class="f6re5nbed"/><path class="ktwgrg95p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magnet-field" {...props}></Icon>
<style>
:global(.f6re5nbed) {
  width: 6px;
  height: 4px;
  x: 12px;
  y: 10px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ktwgrg95p) {
  d: path("M2.75 12H6m12 0h3.25M6 11c-5-8.5 17-8.5 12 0M6 13c-5 8.5 17 8.5 12 0");
}

:global(.mfxvsbbqy) {
  width: 6px;
  height: 4px;
  x: 6px;
  y: 10px;
  rx: 1px;
}

</style>

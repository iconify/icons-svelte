<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekb2lnbaz"/><path class="j_4k-bcfw"/><path class="gcalxb98a"/><path class="hclo6jb2r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:carbon-monoxide-alarm-duotone-thin" {...props}></Icon>
<style>
:global(.ekb2lnbaz) {
  fill: currentColor;
  d: path("M4 10a8 8 0 0 1 16 0v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j_4k-bcfw) {
  d: path("M4 10a8 8 0 0 1 16 0v8a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>

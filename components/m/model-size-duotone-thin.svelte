<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ugww-4jxa"/><path class="tl2b-zblk"/><path class="i3nsbzblu"/><path class="rg7tj2b_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-size-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3nsbzblu) {
  d: path("m10 3 7 7 -7 7 -7 -7Z");
}

:global(.rg7tj2b_x) {
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
}

:global(.tl2b-zblk) {
  fill: currentColor;
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ugww-4jxa) {
  fill: currentColor;
  d: path("m10 3 7 7 -7 7 -7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

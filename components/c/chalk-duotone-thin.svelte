<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfw-_qbdb"/><path class="wy_ebz_tz"/><path class="p8527rbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chalk-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8527rbyx) {
  d: path("m7 15 4 4");
}

:global(.rfw-_qbdb) {
  fill: currentColor;
  d: path("M5 17 15 7l4 4L9 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wy_ebz_tz) {
  d: path("M5 17 15 7l4 4L9 21Z");
}

</style>

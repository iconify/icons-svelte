<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afqgjebgv"/><path class="a37_hz5ge"/><path class="rqvtrb2by"/><path class="m68wh_s2h"/><path class="lgv20g91n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:postfilter-duotone-thin" {...props}></Icon>
<style>
:global(.a37_hz5ge) {
  fill: currentColor;
  d: path("M3 11h18l-7 7v4h-4v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.afqgjebgv) {
  fill: currentColor;
  d: path("M5.5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lgv20g91n) {
  d: path("M3 11h18l-7 7v4h-4v-4Z");
}

:global(.m68wh_s2h) {
  d: path("m10.5 7 2 2");
}

:global(.rqvtrb2by) {
  d: path("M5.5 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

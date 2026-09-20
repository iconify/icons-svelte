<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lzzpbebvm"/><path class="m5a60cbkw"/><path class="xgscl2bdj"/><path class="mypzt1bhf"/><path class="mziob6b8n"/><path class="erjujyioh"/><path class="hrm50umfz"/><path class="lwlflab4b"/><path class="zirb-hbnv"/><path class="n0hr0gbrt"/><path class="s24u-_b8l"/><path class="d-_u6mtyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:braille-duotone-bold" {...props}></Icon>
<style>
:global(.d-_u6mtyl) {
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.erjujyioh) {
  fill: currentColor;
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hrm50umfz) {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lwlflab4b) {
  d: path("M14 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lzzpbebvm) {
  fill: currentColor;
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m5a60cbkw) {
  fill: currentColor;
  d: path("M14 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mypzt1bhf) {
  fill: currentColor;
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mziob6b8n) {
  fill: currentColor;
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s24u-_b8l) {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xgscl2bdj) {
  fill: currentColor;
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

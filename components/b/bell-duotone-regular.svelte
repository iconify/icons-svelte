<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wm7ubgban"/><path class="m3ssv-hnl"/><path class="a74zmrvnc"/><path class="lq830ccix"/><path class="u5jltjbuw"/><path class="xd3fvew_d"/><path class="n5-apabry"/><path class="k4j9-ccbl"/><path class="ok9ioqb8x"/><path class="k-jt90-vx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bell-duotone-regular" {...props}></Icon>
<style>
:global(.a74zmrvnc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-jt90-vx) {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k4j9-ccbl) {
  d: path("M18 13v4");
}

:global(.lq830ccix) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m3ssv-hnl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n5-apabry) {
  d: path("M6 13v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.u5jltjbuw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wm7ubgban) {
  fill: currentColor;
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xd3fvew_d) {
  d: path("M6 13a6 6 0 0 1 12 0");
}

</style>

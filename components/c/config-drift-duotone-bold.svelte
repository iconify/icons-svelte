<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l46grxbhs"/><path class="a85y0t8_i"/><path class="nu0ti3ggl"/><path class="gam3cw54g"/><path class="vhnbtvbtn"/><path class="d4rfzbb0c"/><path class="ys-dg812g"/><path class="wtfq6b2ta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:config-drift-duotone-bold" {...props}></Icon>
<style>
:global(.a85y0t8_i) {
  fill: currentColor;
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d4rfzbb0c) {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gam3cw54g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l46grxbhs) {
  fill: currentColor;
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nu0ti3ggl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.wtfq6b2ta) {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>

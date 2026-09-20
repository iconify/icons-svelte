<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmme25bmv"/><path class="mziob6b8n"/><path class="erjujyioh"/><path class="lp3etd4mx"/><path class="lh_8lcb-x"/><path class="tk9hd5usx"/><path class="s24u-_b8l"/><path class="d-_u6mtyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:claw-machine-duotone-thin" {...props}></Icon>
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

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lh_8lcb-x) {
  d: path("M12 4v6");
}

:global(.lp3etd4mx) {
  d: path("M3 4v17h18V4Z");
}

:global(.mziob6b8n) {
  fill: currentColor;
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qmme25bmv) {
  fill: currentColor;
  d: path("M3 4v17h18V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s24u-_b8l) {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tk9hd5usx) {
  d: path("m9 13 3 -3 3 3");
}

</style>

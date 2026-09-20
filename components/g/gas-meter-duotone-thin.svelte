<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lzs7oacss"/><path class="tbr--mb3k"/><path class="lxc0b_rlj"/><path class="xedmbxbzm"/><path class="rb6wzfbrj"/><path class="p0_y5_ieo"/><path class="tyc7ybeyo"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gas-meter-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lxc0b_rlj) {
  d: path("M5 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.lzs7oacss) {
  fill: currentColor;
  d: path("M5 10a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.p0_y5_ieo) {
  d: path("M6 17v4");
}

:global(.rb6wzfbrj) {
  d: path("M12 10V5");
}

:global(.tbr--mb3k) {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tyc7ybeyo) {
  d: path("M18 17v4");
}

:global(.xedmbxbzm) {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

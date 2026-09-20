<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpl84_dhy"/><path class="wc595gblk"/><path class="fozhwebbv"/><path class="bo88vlbuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:get-together-outline-thin" {...props}></Icon>
<style>
:global(.bo88vlbuz) {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zpl84_dhy) {
  d: path("M12 14c5 0 9 1.5 9 3.5S17 21 12 21s-9 -1.5 -9 -3.5S7 14 12 14");
}

</style>

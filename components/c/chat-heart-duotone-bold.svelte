<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uojx2-ana"/><path class="nnuhlbcty"/><path class="x_lkvk_2h"/><path class="ebuv7_btt"/><path class="x5dchcu_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chat-heart-duotone-bold" {...props}></Icon>
<style>
:global(.ebuv7_btt) {
  d: path("M7 17v3l3 -3");
}

:global(.nnuhlbcty) {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uojx2-ana) {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x_lkvk_2h) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.x5dchcu_y) {
  d: path("M8 9a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

</style>

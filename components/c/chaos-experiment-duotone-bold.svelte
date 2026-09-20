<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rbhvgpbis"/><path class="lzogy7svx"/><path class="xt2uo_lyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chaos-experiment-duotone-bold" {...props}></Icon>
<style>
:global(.lzogy7svx) {
  d: path("M10 3h4v6l6 6v6H4v-6l6 -6Z");
}

:global(.rbhvgpbis) {
  fill: currentColor;
  d: path("M10 3h4v6l6 6v6H4v-6l6 -6Z");
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

:global(.xt2uo_lyl) {
  d: path("m12 12 -3 3h3l-3 3");
}

</style>

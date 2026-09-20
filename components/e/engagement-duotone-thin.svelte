<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xuznnacny"/><path class="qrp1owrzw"/><path class="nrzizubal"/><path class="uu-axlbah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:engagement-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrzizubal) {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.qrp1owrzw) {
  fill: currentColor;
  d: path("m9 8 3 -3 3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uu-axlbah) {
  d: path("m9 8 3 -3 3 3Z");
}

:global(.xuznnacny) {
  fill: currentColor;
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

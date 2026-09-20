<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="awmc0ybgj"/><path class="elusqucks"/><path class="qdz4_8j8r"/><path class="ior2tub3d"/><path class="ab69i60qd"/><path class="ba3_hzrsr"/><path class="d_yxl29go"/><path class="qebvfnl4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-extend-duotone-bold" {...props}></Icon>
<style>
:global(.ab69i60qd) {
  d: path("M5.5 4H3v16h2.5");
}

:global(.awmc0ybgj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ba3_hzrsr) {
  d: path("M7 12h7");
}

:global(.d_yxl29go) {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

:global(.elusqucks) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ior2tub3d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 4H21v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qdz4_8j8r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qebvfnl4i) {
  d: path("M18.5 4H21v16h-2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

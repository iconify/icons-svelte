<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zukkboblc"/><path class="k-u6mjjod"/><path class="pt53q58vo"/><path class="dg3fyzrsp"/><path class="holoa3bic"/><path class="q95wyyyjq"/><path class="t407ddc6o"/><path class="dcemxxfpc"/><path class="uv_v7wb2g"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:few-shot-duotone-bold" {...props}></Icon>
<style>
:global(.dcemxxfpc) {
  d: path("M3 19h8");
}

:global(.dg3fyzrsp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.holoa3bic) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-u6mjjod) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pt53q58vo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q95wyyyjq) {
  d: path("M3 5h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t407ddc6o) {
  d: path("M3 12h8");
}

:global(.uv_v7wb2g) {
  d: path("M14 12h5");
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

:global(.zukkboblc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

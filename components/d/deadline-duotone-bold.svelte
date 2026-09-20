<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e-48xt6xm"/><path class="ykk9winxx"/><path class="ot6fqe_uf"/><path class="ttvusebsk"/><path class="oe2u-obal"/><path class="u4_zcfcdm"/><path class="qaaffjxln"/><path class="fhbl5kbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deadline-duotone-bold" {...props}></Icon>
<style>
:global(.e-48xt6xm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.96 5.66a7 7 0 1 1 -5.92 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fhbl5kbmk) {
  d: path("M21 3v18");
}

:global(.oe2u-obal) {
  d: path("M12.96 5.66a7 7 0 1 1 -5.92 0");
}

:global(.ot6fqe_uf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qaaffjxln) {
  d: path("M10 12h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ttvusebsk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u4_zcfcdm) {
  d: path("M10 7v5");
}

:global(.ykk9winxx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

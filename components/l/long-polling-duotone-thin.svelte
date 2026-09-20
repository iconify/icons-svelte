<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u9-qnozzt"/><path class="ior14cbcm"/><path class="lnfd2u5-f"/><path class="kzz4_xbwx"/><path class="yn7vn5myb"/><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:long-polling-duotone-thin" {...props}></Icon>
<style>
:global(.bxa1b1bso) {
  d: path("M6 5v14");
}

:global(.fr472ib_x) {
  d: path("m13 16 3 3 3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kzz4_xbwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lnfd2u5-f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u9-qnozzt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7g1r9bby) {
  d: path("M16 5v14");
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.yn7vn5myb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>

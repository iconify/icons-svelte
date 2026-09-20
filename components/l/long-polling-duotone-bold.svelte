<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vx9rskbcr"/><path class="d5b4fcc2f"/><path class="b_pnozb_e"/><path class="p2leukl8g"/><path class="bm3gehbwy"/><path class="xf07dvr8m"/><path class="z9ittvbis"/><path class="bxa1b1bso"/><path class="x7g1r9bby"/><path class="fr472ib_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:long-polling-duotone-bold" {...props}></Icon>
<style>
:global(.b_pnozb_e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bm3gehbwy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bxa1b1bso) {
  d: path("M6 5v14");
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fr472ib_x) {
  d: path("m13 16 3 3 3 -3");
}

:global(.p2leukl8g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vx9rskbcr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x7g1r9bby) {
  d: path("M16 5v14");
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>

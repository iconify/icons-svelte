<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="seu_cldqs"/><path class="czz519bgf"/><path class="nb601ouxt"/><path class="u0w287b5g"/><path class="g6e5e7bhp"/><path class="p4c11pbyi"/><path class="ng7_l5bbi"/><path class="qgimpuszh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:glacier-duotone-bold" {...props}></Icon>
<style>
:global(.czz519bgf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 15 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6e5e7bhp) {
  d: path("m2 8 6 6 6 -6 6 6");
}

:global(.nb601ouxt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ng7_l5bbi) {
  d: path("m6 4 4 4");
}

:global(.p4c11pbyi) {
  d: path("m2 15 6 6 6 -6 6 6");
}

:global(.qgimpuszh) {
  d: path("m14 4 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.seu_cldqs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 8 6 6 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u0w287b5g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

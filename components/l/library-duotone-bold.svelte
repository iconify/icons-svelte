<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ci4ma8bed"/><path class="qz9_3ub7s"/><path class="vv5wcibip"/><path class="p04ylgbfu"/><path class="woetzacvo"/><path class="dznv025mt"/><path class="taxmbub4q"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:library-duotone-bold" {...props}></Icon>
<style>
:global(.ci4ma8bed) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 12 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.p04ylgbfu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qz9_3ub7s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.taxmbub4q) {
  d: path("M6 17h12");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

:global(.vv5wcibip) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.woetzacvo) {
  d: path("m4 12 8 -8 8 8");
}

</style>

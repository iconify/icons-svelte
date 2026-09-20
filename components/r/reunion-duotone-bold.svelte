<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g6btd475d"/><path class="bkuclybie"/><path class="nhuoj68-w"/><path class="k3y3of35k"/><path class="b_k90qber"/><path class="mn-a1zb6m"/><path class="e2kgfl2ea"/><path class="s25-orfog"/><path class="jv3d31_7h"/><path class="mqnae981n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reunion-duotone-bold" {...props}></Icon>
<style>
:global(.b_k90qber) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 11 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bkuclybie) {
  fill: currentColor;
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e2kgfl2ea) {
  d: path("M2 15a3 3 0 0 1 6 0");
}

:global(.g6btd475d) {
  fill: currentColor;
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jv3d31_7h) {
  d: path("M16 15a3 3 0 0 1 6 0");
}

:global(.k3y3of35k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mn-a1zb6m) {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mqnae981n) {
  d: path("m9 11 3 3 3 -3");
}

:global(.nhuoj68-w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s25-orfog) {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

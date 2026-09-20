<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wg2m_ib1c"/><path class="wq0on2buw"/><path class="q1wra3bex"/><path class="zlf0p6b7k"/><path class="qj71t0baf"/><path class="t_rr8ablw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flashcard-flip-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1wra3bex) {
  d: path("M2 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qj71t0baf) {
  d: path("M4 19h8");
}

:global(.t_rr8ablw) {
  d: path("m7 16 -3 3 3 3");
}

:global(.wg2m_ib1c) {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wq0on2buw) {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zlf0p6b7k) {
  d: path("M8 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
}

</style>

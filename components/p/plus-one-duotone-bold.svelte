<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnwdi1b1d"/><path class="hfnl5absx"/><path class="q35jisfed"/><path class="g4-jrtbkh"/><path class="kiotcqdhe"/><path class="xiot9nbkk"/><path class="d3kpl_b4o"/><path class="z89se__dl"/><path class="lwq-egybw"/><path class="rn-lfebhh"/><path class="dv5etjbjr"/><path class="x58_p1b1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plus-one-duotone-bold" {...props}></Icon>
<style>
:global(.d3kpl_b4o) {
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dv5etjbjr) {
  d: path("M19.5 8v6");
}

:global(.g4-jrtbkh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hfnl5absx) {
  fill: currentColor;
  d: path("M13 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kiotcqdhe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.5 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lwq-egybw) {
  d: path("M13 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.q35jisfed) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rn-lfebhh) {
  d: path("M12 15a3 3 0 0 1 6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x58_p1b1n) {
  d: path("M17 11h5");
}

:global(.xiot9nbkk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xnwdi1b1d) {
  fill: currentColor;
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z89se__dl) {
  d: path("M4 15a3 3 0 0 1 6 0");
}

</style>

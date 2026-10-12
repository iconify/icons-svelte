<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qdb3h4bwo"/><circle class="z_9qmublw"/><circle class="sotefpb_j"/><circle class="vqkzskxhk"/><circle class="j-nbjixte"/><path class="mrhjebcmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:carpool" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-nbjixte) {
  cx: 15px;
  cy: 4.25px;
  r: 1.5px;
}

:global(.mrhjebcmp) {
  d: path("M7 10a2 2 0 0 1 4 0m2 0a2 2 0 0 1 4 0");
}

:global(.qdb3h4bwo) {
  d: path("M2.75 16.25zq0-1 .97-1.22l1.31-.31q.97-.22 1.63-.97l.68-.75Q8 12.25 9 12.25h6q1 0 1.66.75l.68.75q.66.75 1.63.97l1.31.31q.97.22.97 1.22t-1 1H3.75q-1 0-1-1");
}

:global(.sotefpb_j) {
  cx: 17px;
  cy: 19.25px;
  r: 2px;
}

:global(.vqkzskxhk) {
  cx: 9px;
  cy: 4.25px;
  r: 1.5px;
}

:global(.z_9qmublw) {
  cx: 7px;
  cy: 19.25px;
  r: 2px;
}

</style>

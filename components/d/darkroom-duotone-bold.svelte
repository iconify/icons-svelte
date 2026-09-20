<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h033mmb1s"/><path class="h68oqyb7w"/><path class="h8mw02bqq"/><path class="xp32bq_mk"/><path class="c7dgfu7wx"/><path class="n-z4jv76k"/><path class="qagp93bmg"/><path class="diaqyhfcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:darkroom-duotone-bold" {...props}></Icon>
<style>
:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.diaqyhfcp) {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h033mmb1s) {
  fill: currentColor;
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h68oqyb7w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h8mw02bqq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v14h10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n-z4jv76k) {
  d: path("M7 4v14h10V4");
}

:global(.qagp93bmg) {
  d: path("m9 14 3 -3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xp32bq_mk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 14 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

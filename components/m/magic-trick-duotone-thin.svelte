<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v23dk-htm"/><path class="xvl0zubxy"/><path class="ed6f0ubpi"/><path class="u-ttcyber"/><path class="hf_gtezns"/><path class="p0leisbvy"/><path class="xyj-l9cjp"/><path class="kex2cdcje"/><path class="r7dhdp-mq"/><path class="oq9ztqbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magic-trick-duotone-thin" {...props}></Icon>
<style>
:global(.ed6f0ubpi) {
  fill: currentColor;
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kex2cdcje) {
  d: path("M18 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.oq9ztqbxu) {
  d: path("M11 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p0leisbvy) {
  d: path("M7 18V9h10v9");
}

:global(.r7dhdp-mq) {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.u-ttcyber) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 18V9h10v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v23dk-htm) {
  fill: currentColor;
  d: path("M18 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xvl0zubxy) {
  fill: currentColor;
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>

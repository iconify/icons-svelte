<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="txx5uqbdb"/><path class="sl0tqnboi"/><path class="yf0ac-1wm"/><path class="vrzeiketi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:freshness-check-duotone-bold" {...props}></Icon>
<style>
:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sl0tqnboi) {
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.txx5uqbdb) {
  fill: currentColor;
  d: path("M4 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vrzeiketi) {
  d: path("m16 15 2 2 4 -4");
}

:global(.yf0ac-1wm) {
  d: path("M10 9v3h3");
}

</style>

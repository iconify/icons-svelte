<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="askgmhbjk"/><path class="rwqrrdbai"/><path class="hh5c5wgme"/><path class="bfi7-obrv"/><path class="jgk39zb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:detokenize-outline-bold" {...props}></Icon>
<style>
:global(.askgmhbjk) {
  d: path("M3 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bfi7-obrv) {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

:global(.hh5c5wgme) {
  d: path("M15 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.jgk39zb1b) {
  d: path("M4 18.5h16");
}

:global(.rwqrrdbai) {
  d: path("M9 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

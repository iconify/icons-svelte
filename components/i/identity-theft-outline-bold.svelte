<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="okud9xj_d"/><path class="gwl0nvbom"/><path class="mxs2onbso"/><path class="nse9uf-8v"/><path class="pojccnb-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:identity-theft-outline-bold" {...props}></Icon>
<style>
:global(.gwl0nvbom) {
  d: path("M6 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.mxs2onbso) {
  d: path("M5 15h6");
}

:global(.nse9uf-8v) {
  d: path("m14 9 5 5");
}

:global(.okud9xj_d) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.pojccnb-b) {
  d: path("m19 9 -5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

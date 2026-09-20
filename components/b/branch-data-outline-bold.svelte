<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ftqzjnb8u"/><path class="wc595gblk"/><path class="db6bvvb_j"/><path class="u42rpbb1t"/><path class="fz6e7vbzb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:branch-data-outline-bold" {...props}></Icon>
<style>
:global(.db6bvvb_j) {
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.fz6e7vbzb) {
  d: path("M5 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u42rpbb1t) {
  d: path("M6 12h12v3");
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

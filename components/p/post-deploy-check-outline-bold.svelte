<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ri2m-q_tv"/><path class="e5k2eotmk"/><path class="ei5j_bckv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:post-deploy-check-outline-bold" {...props}></Icon>
<style>
:global(.e5k2eotmk) {
  d: path("M9 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ei5j_bckv) {
  d: path("M11.5 11.5 15 15");
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

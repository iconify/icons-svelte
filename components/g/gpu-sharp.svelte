<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nftlfbbwt"/><path class="s_kkqzb4i"/><path class="rlq0cwfub"/><path class="u5gt8rbgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gpu-sharp" {...props}></Icon>
<style>
:global(.nftlfbbwt) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5v11.5H2.75z");
}

:global(.rlq0cwfub) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11h.01M16 11h.01");
}

:global(.s_kkqzb4i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.25a2.75 2.75 0 1 1 0 5.5a2.75 2.75 0 1 1 0-5.5m8 0a2.75 2.75 0 1 1 0 5.5a2.75 2.75 0 1 1 0-5.5");
}

:global(.u5gt8rbgg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 16.75v3h8.5v-3");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

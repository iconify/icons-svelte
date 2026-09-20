<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k_k2t6-nh"/><path class="q8-0ejn0y"/><path class="igyz-cc5b"/><path class="pt73j1ikv"/><path class="mlfk3xi6j"/><path class="y4qjbbcmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:active-users-duotone-bold" {...props}></Icon>
<style>
:global(.igyz-cc5b) {
  d: path("M3 20a5 5 0 0 1 10 0");
}

:global(.k_k2t6-nh) {
  fill: currentColor;
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mlfk3xi6j) {
  d: path("M18 10v10");
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.q8-0ejn0y) {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y4qjbbcmm) {
  d: path("M21 6v14");
}

</style>

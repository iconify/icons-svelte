<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j5hk4ybky"/><path class="ikqg-2bma"/><path class="y1xrshbyn"/><path class="h51gqww2n"/><path class="bm68p9f0y"/><path class="nmiqo4b0f"/><path class="ec5tld62j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:revenue-goal-duotone-bold" {...props}></Icon>
<style>
:global(.bm68p9f0y) {
  d: path("M6.5 10.5v3");
}

:global(.ec5tld62j) {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h51gqww2n) {
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.ikqg-2bma) {
  fill: currentColor;
  d: path("M14 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j5hk4ybky) {
  fill: currentColor;
  d: path("M2 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nmiqo4b0f) {
  d: path("M14 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y1xrshbyn) {
  fill: currentColor;
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

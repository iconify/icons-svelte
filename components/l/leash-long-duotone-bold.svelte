<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ldg0adrzx"/><path class="n_5sjmbib"/><path class="ja82agbmj"/><path class="ttbqujc9j"/><path class="m1k1s7nte"/><path class="gyi-tobvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leash-long-duotone-bold" {...props}></Icon>
<style>
:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.ja82agbmj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldg0adrzx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m1k1s7nte) {
  d: path("M10 12h10");
}

:global(.n_5sjmbib) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ttbqujc9j) {
  d: path("M7.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>

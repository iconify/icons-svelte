<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="ocqnsc44w"/><path class="o9nm0ibif"/><path class="mebjldn5a"/><path class="t2rd8jbcx"/><path class="z8g2jgblp"/><path class="h_p-57bvu"/><path class="bo51iypxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confidence-interval-duotone-bold" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h_p-57bvu) {
  d: path("M19 8v8");
}

:global(.mebjldn5a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o9nm0ibif) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ocqnsc44w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t2rd8jbcx) {
  d: path("M5 8v8");
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>

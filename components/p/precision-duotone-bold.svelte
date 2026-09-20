<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zwjmk5b0j"/><path class="z3eyrdd0c"/><path class="u6ckfiv0g"/><path class="hfg-g6b7u"/><path class="e7q8l6x6g"/><path class="esqrnvsht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:precision-duotone-bold" {...props}></Icon>
<style>
:global(.e7q8l6x6g) {
  d: path("M6 14h5");
}

:global(.esqrnvsht) {
  d: path("M6 18h7.5");
}

:global(.hfg-g6b7u) {
  d: path("M6 10h7.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u6ckfiv0g) {
  d: path("M6 6h5");
}

:global(.z3eyrdd0c) {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.zwjmk5b0j) {
  fill: currentColor;
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

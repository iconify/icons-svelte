<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="imqf40bqj"/><path class="ga-755bvs"/><path class="cr3csqnmb"/><path class="gljey2tgk"/><path class="pqzdmxnfr"/><path class="ygm75acdx"/><path class="wf5lx0b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hotfix-duotone-regular" {...props}></Icon>
<style>
:global(.cr3csqnmb) {
  fill: currentColor;
  d: path("M18 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ga-755bvs) {
  fill: currentColor;
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gljey2tgk) {
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.imqf40bqj) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqzdmxnfr) {
  d: path("M10 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

:global(.wf5lx0b1p) {
  d: path("M18 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ygm75acdx) {
  d: path("M19 2v3.5");
}

</style>

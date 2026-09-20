<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="its1e1bwq"/><path class="dbfzjzb3n"/><path class="mlcmntxxm"/><path class="r99x8ebjw"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="aeqgdde5a"/><path class="pd0q9ub5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cross-join-duotone-regular" {...props}></Icon>
<style>
:global(.aeqgdde5a) {
  d: path("m7 6 10 10");
}

:global(.dbfzjzb3n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.its1e1bwq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mlcmntxxm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 6 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pd0q9ub5m) {
  d: path("M17 6 7 16");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.r99x8ebjw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 6 7 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>

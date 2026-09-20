<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5fdplbdv"/><path class="nkn0m9bqe"/><path class="dzbcwvq-w"/><path class="itq_ntb3g"/><path class="gv5aqrbwu"/><path class="n53lfdc0t"/><path class="pkt304bvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dentist-chair-duotone-regular" {...props}></Icon>
<style>
:global(.dzbcwvq-w) {
  d: path("M3 16v-4h16v4Z");
}

:global(.gv5aqrbwu) {
  d: path("M7 21h8");
}

:global(.itq_ntb3g) {
  d: path("M11 16v5");
}

:global(.k5fdplbdv) {
  fill: currentColor;
  d: path("M3 16v-4h16v4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n53lfdc0t) {
  d: path("M16 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nkn0m9bqe) {
  fill: currentColor;
  d: path("M16 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

:global(.pkt304bvs) {
  d: path("M19 8v4");
}

</style>

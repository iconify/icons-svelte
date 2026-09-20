<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymw3aibdo"/><path class="mhnr27bap"/><path class="fx4s06o2o"/><path class="cwioy_h_g"/><path class="nggq41d_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:explain-plan-outline-bold" {...props}></Icon>
<style>
:global(.cwioy_h_g) {
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fx4s06o2o) {
  d: path("M6 13v-3h12v3");
}

:global(.mhnr27bap) {
  d: path("M12 7v3");
}

:global(.nggq41d_a) {
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

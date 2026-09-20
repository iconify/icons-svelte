<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c_mfncbzl"/><path class="rj_yrybsf"/><path class="axg5c-q0a"/><path class="nzb-j6sxx"/><path class="k43ew0kyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:federated-query-outline-regular" {...props}></Icon>
<style>
:global(.axg5c-q0a) {
  d: path("M6 10v2.5h12V10");
}

:global(.c_mfncbzl) {
  d: path("M2 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.k43ew0kyq) {
  d: path("M6 17a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzb-j6sxx) {
  d: path("M12 12.5V15");
}

:global(.rj_yrybsf) {
  d: path("M14 5a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>

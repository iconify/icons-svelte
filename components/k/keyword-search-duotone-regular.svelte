<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="a-bghpu3d"/><path class="zls5rf_kj"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="strt8mboj"/><path class="p8yct170k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keyword-search-duotone-regular" {...props}></Icon>
<style>
:global(.a-bghpu3d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8yct170k) {
  d: path("M7 12h6");
}

:global(.qa-jr78us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.strt8mboj) {
  d: path("M7 8h6");
}

:global(.vxtvt1e5w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zls5rf_kj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

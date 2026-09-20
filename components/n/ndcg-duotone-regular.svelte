<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxtvt1e5w"/><path class="qa-jr78us"/><path class="juh5olbuz"/><path class="idwtu_1-i"/><path class="ix1tbe7iy"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="lip701r7h"/><path class="kikp0-sku"/><path class="jsj5j3bdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ndcg-duotone-regular" {...props}></Icon>
<style>
:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.idwtu_1-i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 9v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ix1tbe7iy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 10.5V13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jsj5j3bdw) {
  d: path("M13 10.5V13");
}

:global(.juh5olbuz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.kikp0-sku) {
  d: path("M10 9v4");
}

:global(.lip701r7h) {
  d: path("M7 7v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qa-jr78us) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vxtvt1e5w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n5v54kp1e"/><path class="tz-vspsaw"/><path class="gktwf2bvs"/><path class="to528to2t"/><path class="ri2m-q_tv"/><path class="e3dlplb2a"/><path class="gyrsppg8d"/><path class="g45hqpb0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deploy-window-duotone-regular" {...props}></Icon>
<style>
:global(.e3dlplb2a) {
  d: path("M10.5 9H8v6h2.5");
}

:global(.g45hqpb0s) {
  d: path("M10.5 12h3");
}

:global(.gktwf2bvs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 9H16v6h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gyrsppg8d) {
  d: path("M13.5 9H16v6h-2.5");
}

:global(.n5v54kp1e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.to528to2t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tz-vspsaw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10.5 9H8v6h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

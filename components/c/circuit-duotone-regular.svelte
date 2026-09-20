<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujtuebbmd"/><path class="zndks8byv"/><path class="r4indybxp"/><path class="hu53i5-5k"/><path class="vlo76ab2r"/><path class="qfgxpvbvs"/><path class="qrffjub9u"/><path class="xcm-54bzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-duotone-regular" {...props}></Icon>
<style>
:global(.hu53i5-5k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 17h5V7h6v10h6v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qfgxpvbvs) {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qrffjub9u) {
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.r4indybxp) {
  fill: currentColor;
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ujtuebbmd) {
  fill: currentColor;
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vlo76ab2r) {
  d: path("M2 17h5V7h6v10h6v-7");
}

:global(.xcm-54bzl) {
  d: path("M18 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zndks8byv) {
  fill: currentColor;
  d: path("M12 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

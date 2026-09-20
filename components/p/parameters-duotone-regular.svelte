<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mujv0vbff"/><path class="gof-i4beu"/><path class="d_7om_d_v"/><path class="edjg_qbgi"/><path class="gg9qhlhxo"/><path class="pa1ot6bmg"/><path class="g9_eu8bfj"/><path class="fsi7fbbnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parameters-duotone-regular" {...props}></Icon>
<style>
:global(.d_7om_d_v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.5 9h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.edjg_qbgi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13.5 15h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fsi7fbbnr) {
  d: path("M13.5 15h5");
}

:global(.g9_eu8bfj) {
  d: path("M5.5 9h5");
}

:global(.gg9qhlhxo) {
  d: path("M8 4v16");
}

:global(.gof-i4beu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mujv0vbff) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pa1ot6bmg) {
  d: path("M16 4v16");
}

</style>

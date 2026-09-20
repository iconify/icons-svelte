<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mujv0vbff"/><path class="nxfn3k-cr"/><path class="gof-i4beu"/><path class="tayor0bou"/><path class="gg9qhlhxo"/><path class="v5g-gqbwm"/><path class="pa1ot6bmg"/><path class="wm_1lkfim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-up-duotone-regular" {...props}></Icon>
<style>
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

:global(.nxfn3k-cr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 16 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pa1ot6bmg) {
  d: path("M16 4v16");
}

:global(.tayor0bou) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v5g-gqbwm) {
  d: path("m4 16 4 4 4 -4");
}

:global(.wm_1lkfim) {
  d: path("m12 8 4 -4 4 4");
}

</style>

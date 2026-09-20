<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7k_twb0c"/><path class="xb0ugqbkt"/><path class="h5t6wxitw"/><path class="gedzti5ut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-protocol-outline-regular" {...props}></Icon>
<style>
:global(.gedzti5ut) {
  d: path("m12 14.5 2.5 -2.5");
}

:global(.h5t6wxitw) {
  d: path("M9.5 12 12 9.5");
}

:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xb0ugqbkt) {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

</style>

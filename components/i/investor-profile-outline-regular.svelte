<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w08657bnd"/><path class="f-g-_s4ku"/><path class="yngda3bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:investor-profile-outline-regular" {...props}></Icon>
<style>
:global(.f-g-_s4ku) {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w08657bnd) {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>

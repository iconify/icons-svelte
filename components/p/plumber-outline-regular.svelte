<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="lna_zyjca"/><path class="tukmg9l1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plumber-outline-regular" {...props}></Icon>
<style>
:global(.fqjewfbna) {
  d: path("M2 16a4 4 0 0 1 8 0");
}

:global(.k74vnib1e) {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.lna_zyjca) {
  d: path("m13 20 4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tukmg9l1f) {
  d: path("M21.12 15.12a3 3 0 1 1 0 -4.24");
}

</style>

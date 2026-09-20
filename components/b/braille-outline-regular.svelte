<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hrm50umfz"/><path class="lwlflab4b"/><path class="zirb-hbnv"/><path class="n0hr0gbrt"/><path class="s24u-_b8l"/><path class="d-_u6mtyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:braille-outline-regular" {...props}></Icon>
<style>
:global(.d-_u6mtyl) {
  d: path("M14 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hrm50umfz) {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.lwlflab4b) {
  d: path("M14 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n0hr0gbrt) {
  d: path("M14 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s24u-_b8l) {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

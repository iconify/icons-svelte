<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6clf9bgd"/><path class="fs_osxb0l"/><path class="ocgq8oo_l"/><path class="zqoml3bvy"/><path class="oe2rn1bbo"/><path class="gtsw5xviq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leash-short-duotone-regular" {...props}></Icon>
<style>
:global(.fs_osxb0l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gtsw5xviq) {
  d: path("M17 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ocgq8oo_l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oe2rn1bbo) {
  d: path("M14 12h3");
}

:global(.q6clf9bgd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zqoml3bvy) {
  d: path("M11.11 7.47a5 5 0 1 1 -4.22 0");
}

</style>

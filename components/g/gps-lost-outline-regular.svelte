<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zey5ebc0a"/><path class="q3srlnbfr"/><path class="c438ceftc"/><path class="l8unaacgj"/><path class="e69i7fcek"/><path class="u363cab-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gps-lost-outline-regular" {...props}></Icon>
<style>
:global(.c438ceftc) {
  d: path("M12 17v5");
}

:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.l8unaacgj) {
  d: path("M2 12h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.u363cab-y) {
  d: path("M5 19 19 5");
}

:global(.zey5ebc0a) {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ka4276blj"/><path class="whta1s4jw"/><path class="ajsbq9bvm"/><path class="wzikiebiw"/><path class="p0mfrtbaw"/><path class="vs9x-_bah"/><path class="hclo6jb2r"/><path class="ubmhydvvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embedding-compare-duotone-regular" {...props}></Icon>
<style>
:global(.ajsbq9bvm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.ka4276blj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0mfrtbaw) {
  d: path("M7.5 5 10 7.5l-4 4 -4 -4L4.5 5");
}

:global(.ubmhydvvx) {
  d: path("M8 19.5h8");
}

:global(.vs9x-_bah) {
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
}

:global(.whta1s4jw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.5 5 22 7.5l-4 4 -4 -4L16.5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wzikiebiw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 19.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

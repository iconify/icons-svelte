<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asd1gsbjs"/><path class="c_sz-g7tz"/><path class="nwdk136nn"/><path class="h91kiclib"/><path class="jcxg2bbvb"/><path class="kaj4_cbkd"/><path class="jlfl_ccwj"/><path class="kes5k2fvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:contradiction-duotone-regular" {...props}></Icon>
<style>
:global(.asd1gsbjs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c_sz-g7tz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h91kiclib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.jlfl_ccwj) {
  d: path("M14 12h8");
}

:global(.kaj4_cbkd) {
  d: path("m6 8 4 4 -4 4");
}

:global(.kes5k2fvf) {
  d: path("m18 8 -4 4 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nwdk136nn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

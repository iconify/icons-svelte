<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="enu67qgvs"/><path class="jrr2xybsm"/><path class="ylx8eyb-q"/><path class="w0as59itk"/><path class="jlfjgzbqx"/><path class="aum97lbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:draft-duotone-regular" {...props}></Icon>
<style>
:global(.aum97lbyp) {
  d: path("M9 13h4");
}

:global(.enu67qgvs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 3H6v18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.jrr2xybsm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w0as59itk) {
  d: path("M13 3H6v18h8");
}

:global(.ylx8eyb-q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 13h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

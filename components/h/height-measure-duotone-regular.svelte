<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iczafxbjt"/><path class="k5yvsiilv"/><path class="dvavr_yjv"/><path class="cuso263ot"/><path class="ezik40n3m"/><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:height-measure-duotone-regular" {...props}></Icon>
<style>
:global(.cuso263ot) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dvavr_yjv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 18 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ezik40n3m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.iczafxbjt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k5yvsiilv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 6 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.tdul-wdwn) {
  d: path("m9 6 3 -3 3 3");
}

:global(.vy337188j) {
  d: path("m9 18 3 3 3 -3");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>

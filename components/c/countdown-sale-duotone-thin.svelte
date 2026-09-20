<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t8qgc60qv"/><path class="ck_r08b8b"/><path class="vgq9q1bvc"/><path class="b6-nnw_wv"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="b266jkbmh"/><path class="m-436sbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:countdown-sale-duotone-thin" {...props}></Icon>
<style>
:global(.b266jkbmh) {
  d: path("M7 3v4l5 5 5 -5V3");
}

:global(.b6-nnw_wv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21v-4l5 -5 5 5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck_r08b8b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-436sbse) {
  d: path("M7 21v-4l5 -5 5 5v4");
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.t8qgc60qv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vgq9q1bvc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3v4l5 5 5 -5V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>

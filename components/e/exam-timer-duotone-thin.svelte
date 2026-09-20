<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t8qgc60qv"/><path class="ck_r08b8b"/><path class="wyj1t5zzw"/><path class="knuk60bkd"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="bdxedv3gx"/><path class="i4nkkkbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exam-timer-duotone-thin" {...props}></Icon>
<style>
:global(.bdxedv3gx) {
  d: path("M6 3v3l6 6 6 -6V3");
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

:global(.i4nkkkbsh) {
  d: path("M6 21v-3l6 -6 6 6v3");
}

:global(.knuk60bkd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21v-3l6 -6 6 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.t8qgc60qv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wyj1t5zzw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v3l6 6 6 -6V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>

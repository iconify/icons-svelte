<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="corfxhbfm"/><path class="fa20jgbno"/><path class="t8qgc60qv"/><path class="ck_r08b8b"/><path class="h2-2dgnfu"/><path class="tdul-wdwn"/><path class="vy337188j"/><path class="rjrs_5bsc"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:height-measure-duotone-thin" {...props}></Icon>
<style>
:global(.ck_r08b8b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.corfxhbfm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 6 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fa20jgbno) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 18 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6n49udox) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.t8qgc60qv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3h12");
  opacity: var(--svg-opacity--0-2, 0.2);
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

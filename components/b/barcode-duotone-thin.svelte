<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tp514yb1s"/><path class="lf5f-7bvs"/><path class="sjvxvsbmk"/><path class="ymccf7box"/><path class="f02t2vblf"/><path class="nkim8cbjd"/><path class="azgrucbqu"/><path class="j5yfc7b4j"/><path class="btdmtu_xg"/><path class="vckqcjbbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barcode-duotone-thin" {...props}></Icon>
<style>
:global(.azgrucbqu) {
  d: path("M7 5v14");
}

:global(.btdmtu_xg) {
  d: path("M14 5v14");
}

:global(.f02t2vblf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j5yfc7b4j) {
  d: path("M11 5v14");
}

:global(.lf5f-7bvs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nkim8cbjd) {
  d: path("M4 5v14");
}

:global(.sjvxvsbmk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tp514yb1s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vckqcjbbb) {
  d: path("M18 5v14");
}

:global(.ymccf7box) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

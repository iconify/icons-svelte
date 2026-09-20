<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kn2e0_xvy"/><path class="kfq3-jb_e"/><path class="wwd4m5b_z"/><path class="kk8g9jb0n"/><path class="ab69i60qd"/><path class="ba3_hzrsr"/><path class="d_yxl29go"/><path class="qebvfnl4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-extend-duotone-thin" {...props}></Icon>
<style>
:global(.ab69i60qd) {
  d: path("M5.5 4H3v16h2.5");
}

:global(.ba3_hzrsr) {
  d: path("M7 12h7");
}

:global(.d_yxl29go) {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfq3-jb_e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kk8g9jb0n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 4H21v16h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn2e0_xvy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qebvfnl4i) {
  d: path("M18.5 4H21v16h-2.5");
}

:global(.wwd4m5b_z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 9.5 16 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

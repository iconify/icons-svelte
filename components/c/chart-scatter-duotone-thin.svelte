<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mk0cvynsk"/><path class="vfk9p6bsw"/><path class="ky48x0b1z"/><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="ynh89jb5g"/><path class="cg4ywvb4m"/><path class="a6m5kfb7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-scatter-duotone-thin" {...props}></Icon>
<style>
:global(.a6m5kfb7k) {
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.cg4ywvb4m) {
  d: path("M12 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ky48x0b1z) {
  fill: currentColor;
  d: path("M18 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mk0cvynsk) {
  fill: currentColor;
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.vfk9p6bsw) {
  fill: currentColor;
  d: path("M12 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ynh89jb5g) {
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

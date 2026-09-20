<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="twudebb9m"/><path class="pdovjob2m"/><path class="avyvkw01i"/><path class="k8jcztb-g"/><path class="u4sowhi7h"/><path class="v85yu_66d"/><path class="ihh3idyew"/><path class="t_-p3gl9a"/><path class="zfnkrabzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:birthday-cake-duotone-thin" {...props}></Icon>
<style>
:global(.avyvkw01i) {
  fill: currentColor;
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ihh3idyew) {
  d: path("M15 8v5");
}

:global(.k8jcztb-g) {
  d: path("M4 13v7h16v-7Z");
}

:global(.pdovjob2m) {
  fill: currentColor;
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t_-p3gl9a) {
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.twudebb9m) {
  fill: currentColor;
  d: path("M4 13v7h16v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.v85yu_66d) {
  d: path("M9 8v5");
}

:global(.zfnkrabzj) {
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

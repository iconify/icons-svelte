<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wz8gtmcjb"/><path class="mqq1vkbnx"/><path class="wo-i6bqjc"/><path class="td_xqobtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:clouds-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mqq1vkbnx) {
  fill: currentColor;
  d: path("M9 21a3.5 3.5 0 0 1 2 -6 4.5 4.5 0 0 1 8 -1 4.5 4.5 0 0 1 3 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.td_xqobtu) {
  d: path("M9 21a3.5 3.5 0 0 1 2 -6 4.5 4.5 0 0 1 8 -1 4.5 4.5 0 0 1 3 7Z");
}

:global(.wo-i6bqjc) {
  d: path("M2 14a3 3 0 0 1 2 -5.5 4 4 0 0 1 7.5 -1A4.5 4.5 0 0 1 15 14Z");
}

:global(.wz8gtmcjb) {
  fill: currentColor;
  d: path("M2 14a3 3 0 0 1 2 -5.5 4 4 0 0 1 7.5 -1A4.5 4.5 0 0 1 15 14Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

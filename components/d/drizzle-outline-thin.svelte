<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-pcdbceg"/><path class="cfjjc4b9u"/><path class="luc_hlbxh"/><path class="k6xu7tbiy"/><path class="doij5pb5x"/><path class="p-vzdvbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drizzle-outline-thin" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.cfjjc4b9u) {
  d: path("m8 17 -2.5 2.5");
}

:global(.doij5pb5x) {
  d: path("M10.5 19.5 8 22");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6xu7tbiy) {
  d: path("m18 17 -2.5 2.5");
}

:global(.luc_hlbxh) {
  d: path("m13 17 -2.5 2.5");
}

:global(.p-vzdvbyx) {
  d: path("M15.5 19.5 13 22");
}

</style>

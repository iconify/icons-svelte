<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myekf3bzc"/><path class="ef626bcbl"/><path class="rrxso7m3p"/><path class="i49-5fazd"/><path class="odx_lab8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:co-op-outline-thin" {...props}></Icon>
<style>
:global(.ef626bcbl) {
  d: path("M3 17a4 4 0 0 1 8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i49-5fazd) {
  d: path("M13 17a4 4 0 0 1 8 0");
}

:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.odx_lab8a) {
  d: path("M10 6h4");
}

:global(.rrxso7m3p) {
  d: path("M14 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

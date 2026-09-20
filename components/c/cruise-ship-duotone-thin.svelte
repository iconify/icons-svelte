<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh-r4db2e"/><path class="r0ugme01d"/><path class="j2rh_abzz"/><path class="lo13e1bkv"/><path class="x212dunwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cruise-ship-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2rh_abzz) {
  d: path("M5 15v-4h14v4");
}

:global(.jh-r4db2e) {
  fill: currentColor;
  d: path("M2 15h20l-5 5H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lo13e1bkv) {
  d: path("M9 11V7h7v4");
}

:global(.r0ugme01d) {
  d: path("M2 15h20l-5 5H7Z");
}

:global(.x212dunwb) {
  d: path("M11 7V3h3v4");
}

</style>

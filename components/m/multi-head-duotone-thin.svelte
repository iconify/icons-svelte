<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jtwp3absz"/><path class="d8c5u6bor"/><path class="uvgrx_yvv"/><path class="phg4z53le"/><path class="jc5wb8hwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multi-head-duotone-thin" {...props}></Icon>
<style>
:global(.d8c5u6bor) {
  d: path("M7 3v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jc5wb8hwy) {
  d: path("m12 11 4 4 -4 4 -4 -4Z");
}

:global(.jtwp3absz) {
  fill: currentColor;
  d: path("m12 11 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.phg4z53le) {
  d: path("M17 3v5");
}

:global(.uvgrx_yvv) {
  d: path("M12 3v5");
}

</style>

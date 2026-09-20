<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1w08ccuz"/><path class="g7ipnac6i"/><path class="icp673bbo"/><path class="pa9quik2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:road-trip-outline-thin" {...props}></Icon>
<style>
:global(.g7ipnac6i) {
  d: path("m21 20 -6 -6V5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.icp673bbo) {
  d: path("M12 9v3");
}

:global(.pa9quik2g) {
  d: path("M12 16v3");
}

:global(.t1w08ccuz) {
  d: path("m3 20 6 -6V5");
}

</style>

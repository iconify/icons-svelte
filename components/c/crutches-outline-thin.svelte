<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yfvv4yzsv"/><path class="py87sqk9l"/><path class="fa77bsbgi"/><path class="bhj229bdw"/><path class="tj33frbke"/><path class="w2atjyb_m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crutches-outline-thin" {...props}></Icon>
<style>
:global(.bhj229bdw) {
  d: path("M14 4h6");
}

:global(.fa77bsbgi) {
  d: path("M4 10h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.py87sqk9l) {
  d: path("M7 4v17");
}

:global(.tj33frbke) {
  d: path("M17 4v17");
}

:global(.w2atjyb_m) {
  d: path("M14 10h6");
}

:global(.yfvv4yzsv) {
  d: path("M4 4h6");
}

</style>

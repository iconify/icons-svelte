<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cacmi2bmi"/><path class="nxt-uwbql"/><path class="j8ahhogzn"/><path class="gxa8_gbhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-resource-subscribe-outline-thin" {...props}></Icon>
<style>
:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.gxa8_gbhz) {
  d: path("M9 17a7 7 0 0 1 7 -7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8ahhogzn) {
  d: path("M12 17a4 4 0 0 1 4 -4");
}

:global(.nxt-uwbql) {
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

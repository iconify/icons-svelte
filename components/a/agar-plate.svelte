<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yqbzscbua"/><path class="j6xzs2bsb"/><path class="xnjrtbc3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agar-plate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6xzs2bsb) {
  d: path("M2.5 9.5v4a9.5 5.5 0 0 0 19 0v-4");
}

:global(.xnjrtbc3s) {
  d: path("M5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.yqbzscbua) {
  d: path("M2.5 9.5a9.5 5.5 0 1 0 19 0a9.5 5.5 0 1 0-19 0");
}

</style>

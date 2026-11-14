<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="meacokyks"/><path class="btc9x7bre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coral-restoration" {...props}></Icon>
<style>
:global(.btc9x7bre) {
  d: path("M3 21q4.858-6.183 9.716-1.443m.579.603q.352.391.705.84m4-6v6m-3-3h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.meacokyks) {
  d: path("M8.5 17.5v-5Q8.5 10 5 9V4.5m3.5 8q0-2.5 4-3.5V4m0 5Q16 8.5 16 5");
}

</style>

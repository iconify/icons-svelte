<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kc9-v-u-y"/><path class="qh8fg0oaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:market-research" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kc9-v-u-y) {
  cx: 10.25px;
  cy: 10.25px;
  r: 6.75px;
}

:global(.qh8fg0oaf) {
  d: path("m15.25 15.25l6 6M7.75 13v-2m2.5 2V7.5m2.5 5.5V9.5");
}

</style>

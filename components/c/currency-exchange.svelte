<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="qtr58-ckh"/><circle class="azpvbcbbw"/><path class="ivdsxccyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:currency-exchange" {...props}></Icon>
<style>
:global(.azpvbcbbw) {
  cx: 16.5px;
  cy: 16.5px;
  r: 4.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivdsxccyn) {
  d: path("M14.5 4.5h2A2.5 2.5 0 0 1 19 7v2.75m-2-2l2 2l2-2M9.5 19.5h-2A2.5 2.5 0 0 1 5 17v-2.75m2 2l-2-2l-2 2");
}

:global(.qtr58-ckh) {
  cx: 7.5px;
  cy: 7.5px;
  r: 4.5px;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="km6u6lbab"/><path class="zd9pcjwtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marker-diamond" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.km6u6lbab) {
  d: path("m13.312 3.987l5.268 5.97a1.75 1.75 0 0 1 .111 2.175l-5.267 7.374a1.75 1.75 0 0 1-2.848 0l-5.267-7.374a1.75 1.75 0 0 1 .111-2.175l5.268-5.97a1.75 1.75 0 0 1 2.624 0");
}

:global(.zd9pcjwtr) {
  d: path("M9.25 11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>

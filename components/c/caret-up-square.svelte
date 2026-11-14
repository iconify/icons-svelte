<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtvi81ccy"/><path class="bf6gh-b4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:caret-up-square" {...props}></Icon>
<style>
:global(.bf6gh-b4d) {
  d: path("m13.161 10.169l1.335 1.631a1.5 1.5 0 0 1-1.161 2.45h-2.67a1.5 1.5 0 0 1-1.161-2.45l1.335-1.631a1.5 1.5 0 0 1 2.322 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mtvi81ccy) {
  d: path("M9.625 3.5h4.75A6.125 6.125 0 0 1 20.5 9.625v4.75a6.125 6.125 0 0 1-6.125 6.125h-4.75A6.125 6.125 0 0 1 3.5 14.375v-4.75A6.125 6.125 0 0 1 9.625 3.5");
}

</style>

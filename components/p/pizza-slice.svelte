<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ais2kobvo"/><path class="ocfrf5bnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pizza-slice" {...props}></Icon>
<style>
:global(.ais2kobvo) {
  d: path("M9.698 16.803L5.632 9.387A2.625 2.625 0 0 1 7.933 5.5h8.134a2.625 2.625 0 0 1 2.301 3.887l-4.066 7.416a2.625 2.625 0 0 1-4.604 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ocfrf5bnq) {
  d: path("M8.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4 2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zx0i7tbao"/><path class="ma2xg8xza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rose-bud" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ma2xg8xza) {
  d: path("M7.25 9.75C10 12 13.5 11 15 5.75m-3 9.75q-2.5.25-5 2.75m5-2.75q2.5.25 5 2.75m-5-2.75v6");
}

:global(.zx0i7tbao) {
  d: path("M12 2.5c3.5 3 5 6.5 5 9c0 2.75-2.25 4-5 4s-5-1.25-5-4c0-2.5 1.5-6 5-9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwso4kaoa"/><path class="w-07libnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:food-waste-donation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pwso4kaoa) {
  d: path("M3 13h5l4 2h4.5a1.5 1.5 0 0 1 0 3h-5");
}

:global(.w-07libnq) {
  d: path("M3 21h11l7-5m-7-5.5L10.5 7A2 2 0 0 1 14 4.5A2 2 0 0 1 17.5 7Z");
}

</style>

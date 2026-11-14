<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iwjpe5xor"/><path class="v8-vjjbdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-dumpling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwjpe5xor) {
  d: path("M3 17c0-6 4-9 9-12.5C17 8 21 11 21 17q0 2.5-2.5 2.5h-13Q3 19.5 3 17");
}

:global(.v8-vjjbdk) {
  d: path("M12 4.5q-2.25 3.5-3 7m3-7q2.25 3.5 3 7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aheou_s8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delivery-door-store" {...props}></Icon>
<style>
:global(.aheou_s8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V3h18v10.4M3 7h18M3 11.5h18M17.25 16h2.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 17.25 16m1.25 0v2.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfh4qpbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:citizen-complaint" {...props}></Icon>
<style>
:global(.dfh4qpbvt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3 13.5c0-4 3-6.75 7-6.75c2.44 0 4.508 1.023 5.75 2.729M18 14.75v3.5M18 21h.01");
}

</style>

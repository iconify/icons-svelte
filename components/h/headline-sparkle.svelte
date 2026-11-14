<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvgivmbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:headline-sparkle" {...props}></Icon>
<style>
:global(.nvgivmbed) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h3.5A3.5 3.5 0 0 1 13 7a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 7A3.5 3.5 0 0 1 6 3.5M5.5 7H10m-7 8.5h18M3 20h11m4.75-16q0 3 3 3q-3 0-3 3q0-3-3-3q3 0 3-3");
}

</style>

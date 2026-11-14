<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np-jamp6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-horror" {...props}></Icon>
<style>
:global(.np-jamp6y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 20.5V10a7 7 0 0 1 14 0v10.5q-1.75-2-3.5 0t-3.5 0t-3.5 0t-3.5 0m4.5-10h.01m4.99 0h.01");
}

</style>

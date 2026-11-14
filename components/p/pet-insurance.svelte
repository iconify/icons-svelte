<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jojo-2blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pet-insurance" {...props}></Icon>
<style>
:global(.jojo-2blr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10a9 7.5 0 0 1 18 0q-3-1.5-6 0q-3-1.5-6 0q-3-1.5-6 0m4.5 3l2.5 2.25h4L16.5 13v4.5a4.5 4 0 0 1-9 0Zm2.75 4.25h.01m3.49 0h.01");
}

</style>

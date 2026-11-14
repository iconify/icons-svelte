<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejua1vb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cordon" {...props}></Icon>
<style>
:global(.ejua1vb2s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5h4m-2 0V4m12 17.5h4m-2 0V4M5 7.5q7 4.5 14 0V11q-7 4.5-14 0Z");
}

</style>

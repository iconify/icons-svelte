<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deh637bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:proportional-to" {...props}></Icon>
<style>
:global(.deh637bka) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 7.5c-2.5 0-4 1.5-5.5 4.5s-3.5 4.5-6.25 4.5S4 14.5 4 12s1.75-4.5 4.25-4.5S13 9 14.5 12s3 4.5 5.5 4.5");
}

</style>

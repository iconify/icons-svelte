<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adw7jhb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bimodal-distribution" {...props}></Icon>
<style>
:global(.adw7jhb4e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C4 20.5 5 6 8 6s3 9 4 9s1-6.5 4-6.5s4 12 5.5 12");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn2jd16hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:review-star" {...props}></Icon>
<style>
:global(.rn2jd16hr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l2.5 5.75l6 .5l-4.5 4l1.5 6.5L12 16.5l-5.5 3.25l1.5-6.5l-4.5-4l6-.5Z");
}

</style>

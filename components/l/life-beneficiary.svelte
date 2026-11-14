<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtdu9w56g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:life-beneficiary" {...props}></Icon>
<style>
:global(.vtdu9w56g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 7a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M8.5 21c0-4 2.5-6 6-6s6 2 6 6m-18-9H9M6.5 9.5L9 12l-2.5 2.5");
}

</style>

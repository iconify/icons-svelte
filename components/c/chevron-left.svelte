<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz2v4ha0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chevron-left" {...props}></Icon>
<style>
:global(.oz2v4ha0k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 18.5L8.5 12L15 5.5");
}

</style>

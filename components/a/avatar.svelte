<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm6tiqt_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:avatar" {...props}></Icon>
<style>
:global(.tm6tiqt_j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M4 21c0-4 3.5-6 8-6s8 2 8 6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj4pxdb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:greater-than" {...props}></Icon>
<style>
:global(.tj4pxdb4z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5L17 12L7 18.5");
}

</style>

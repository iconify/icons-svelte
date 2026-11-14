<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3j-b1bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ellipsis-symbol" {...props}></Icon>
<style>
:global(.v3j-b1bxs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>

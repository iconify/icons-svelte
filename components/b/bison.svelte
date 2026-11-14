<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk606pbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bison" {...props}></Icon>
<style>
:global(.nk606pbma) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8c0-4.5 10-4.5 10 0c0 3-1.5 5-2 7q-.75 4.5-3 4.5T9 15c-.5-2-2-4-2-7m0 0c-2.5.5-4-1-3.5-4M17 8c2.5.5 4-1 3.5-4M10 11h.01M14 11h.01");
}

</style>

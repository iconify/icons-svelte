<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbs2wubsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:buff" {...props}></Icon>
<style>
:global(.qbs2wubsx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.237 4.737l4.114 4.114A.673.673 0 0 1 14.875 10a1.625 1.625 0 0 0-1.625 1.625v7.625A1.75 1.75 0 0 1 11.5 21h-3a1.75 1.75 0 0 1-1.75-1.75v-7.625A1.625 1.625 0 0 0 5.125 10a.673.673 0 0 1-.476-1.149l4.114-4.114a1.75 1.75 0 0 1 2.474 0M19 2.5Q19 5 21.5 5Q19 5 19 7.5Q19 5 16.5 5Q19 5 19 2.5");
}

</style>

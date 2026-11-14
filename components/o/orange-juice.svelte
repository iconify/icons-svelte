<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mkfsbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:orange-juice" {...props}></Icon>
<style>
:global(.w5mkfsbmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5H17l-1 14H5.5Zm7.5 0a4 4 0 0 1 8 0M4.75 11h12M16 7.5L14 4m2 3.5L18 4");
}

</style>

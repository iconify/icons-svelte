<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr_gi0bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:notary-stamp" {...props}></Icon>
<style>
:global(.xr_gi0bcl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 3.5h1.75A2.625 2.625 0 0 1 15.5 6.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 8.875v-2.75A2.625 2.625 0 0 1 11.125 3.5M6 11.5h12v4H6Zm-1 9h14");
}

</style>

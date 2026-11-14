<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1yvnb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:over-under-3d" {...props}></Icon>
<style>
:global(.ps1yvnb-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 2.5h12.75A2.625 2.625 0 0 1 21 5.125v2.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 7.875v-2.75A2.625 2.625 0 0 1 5.625 2.5m0 11h12.75A2.625 2.625 0 0 1 21 16.125v2.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-2.75A2.625 2.625 0 0 1 5.625 13.5");
}

</style>

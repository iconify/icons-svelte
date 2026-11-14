<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5dbz8b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:antenna-plus" {...props}></Icon>
<style>
:global(.z5dbz8b5s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M8.5 7.25V20.5m-3.5 0h7m-.318-18.182a4.5 4.5 0 0 1 0 6.364m-6.364 0a4.5 4.5 0 0 1 0-6.364M18 15v6m-3-3h6");
}

</style>

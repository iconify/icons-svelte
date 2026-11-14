<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgkoaiiny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:brand-font-pair" {...props}></Icon>
<style>
:global(.lgkoaiiny) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5L8.25 4h1l4.816 15.137M5 14.5h7.5m4.25 3.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4.5-2.75v5.25");
}

</style>

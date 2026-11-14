<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoo_mn0pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:error" {...props}></Icon>
<style>
:global(.qoo_mn0pz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m5.25-4.25l8.5 8.5m0-8.5l-8.5 8.5");
}

</style>

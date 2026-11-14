<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_vkxfb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bin-store" {...props}></Icon>
<style>
:global(.o_vkxfb1h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2 10l10-6.5L22 10M4 8.75V21.5M20 8.75V21.5M7.5 11.75h9m-8 0l1 9.75h5l1-9.75");
}

</style>

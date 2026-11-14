<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkmug9u8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:platinum-bar" {...props}></Icon>
<style>
:global(.wkmug9u8s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5h19l-3-8h-13Zm3-8l1.75-5h9.5l1.75 5");
}

</style>

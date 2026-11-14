<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbmhupbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-lowest" {...props}></Icon>
<style>
:global(.wbmhupbyt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 5.5l8 8l8-8m-12 13h8");
}

</style>

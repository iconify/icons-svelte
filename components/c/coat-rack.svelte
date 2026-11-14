<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2v2u1bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coat-rack" {...props}></Icon>
<style>
:global(.i2v2u1bii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v16m-4.5 2.5l4.5-3l4.5 3M7 4.5v2h5M17 8v2h-5");
}

</style>

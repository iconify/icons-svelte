<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc8soy-az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cyrillic-letters" {...props}></Icon>
<style>
:global(.pc8soy-az) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 20V6h8.5M6 12.5h7a3.75 3.75 0 0 1 0 7.5H6M18 6v14");
}

</style>

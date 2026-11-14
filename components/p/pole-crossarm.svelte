<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erk0ycb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pole-crossarm" {...props}></Icon>
<style>
:global(.erk0ycb0j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v18M3 7h18M4.5 7V3.5m15 3.5V3.5M7.5 7l4.5 4.5L16.5 7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um274rbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:acrylic-nails" {...props}></Icon>
<style>
:global(.um274rbge) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5h8L17.5 15c0 3.5-2.5 6-5.5 6s-5.5-2.5-5.5-6Zm2 10l2.5-6");
}

</style>

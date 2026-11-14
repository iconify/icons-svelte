<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6junmoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:midnight-sale" {...props}></Icon>
<style>
:global(.sy6junmoj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 3.5a9 9 0 1 0 9 9a6.5 6.5 0 0 1-9-9m3 7l5-5M15 6h.01M19 10h.01");
}

</style>

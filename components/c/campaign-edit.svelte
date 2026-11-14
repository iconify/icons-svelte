<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5nu1qupl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:campaign-edit" {...props}></Icon>
<style>
:global(.n5nu1qupl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5h4.5l8.5-4v11.25L7.5 10H3ZM5.5 10l1.25 5M15 21v-2.25l4.25-4.25l2.25 2.25L17.25 21Z");
}

</style>

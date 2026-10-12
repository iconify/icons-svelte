<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km3qf_avl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:list-collapse" {...props}></Icon>
<style>
:global(.km3qf_avl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 5.5h9.5m-9.5 6.5h9.5m-9.5 6.5h9.5M3.75 5.25L6 7.5l2.25-2.25m-4.5 13.5L6 16.5l2.25 2.25");
}

</style>

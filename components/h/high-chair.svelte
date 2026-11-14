<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmxs7uboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:high-chair" {...props}></Icon>
<style>
:global(.cmxs7uboj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 5h4.75A2.625 2.625 0 0 1 17 7.625v.75A2.625 2.625 0 0 1 14.375 11h-4.75A2.625 2.625 0 0 1 7 8.375v-.75A2.625 2.625 0 0 1 9.625 5M7 11v9.5M17 11v9.5m-13-6h16m-15 6h14");
}

</style>

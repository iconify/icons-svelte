<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8h5ve7-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:account-guest" {...props}></Icon>
<style>
:global(.h8h5ve7-y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.327 9.435a4 4 0 0 1 0-4.87m2.651-1.531a4 4 0 0 1 4.218 2.435m0 3.062a4 4 0 0 1-4.218 2.435M3 19.5c0-1.5.75-2.75 2-3.75m3.25-1.25c.75-.25 1.5-.5 2.25-.5s1.5.25 2.25.5M16 15.75c1.25 1 2 2.25 2 3.75m-11.75 1h8.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4dq70bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bra" {...props}></Icon>
<style>
:global(.e4dq70bro) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5v-2c0-4 3-7.25 6-8c2 2 3.25 5 3.5 8c.25-3 1.5-6 3.5-8c3 .75 6 4 6 8v2Zm6-10l-1-5m8 5l1-5m-4.5 13v2");
}

</style>

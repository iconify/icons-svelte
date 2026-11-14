<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9un28ajl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bimini-top" {...props}></Icon>
<style>
:global(.v9un28ajl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19c-1 3.5-3 5.5-6.5 5.5H4.5Zm2-7q7.5-3.5 15 0M7 6v8m10-8v8");
}

</style>

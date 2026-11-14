<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avwm4ybhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coasteering" {...props}></Icon>
<style>
:global(.avwm4ybhv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h8L13 6.5L11.5 9l2 2.5h-11ZM3 15.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 20.25q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>

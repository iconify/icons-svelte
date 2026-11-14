<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8ryvkbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nebula-pillars" {...props}></Icon>
<style>
:global(.s8ryvkbdf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21h19M3 21l1.5-9.5q.5-2 1 0L7 21m2.75 0L11.5 7.5q.5-2 1 0L14.25 21M17 21l1.5-6.5q.5-2 1 0L21 21M18.75 3v5m-2.5-2.5h5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywy_b9iff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marine-biologist" {...props}></Icon>
<style>
:global(.ywy_b9iff) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.966 0 1.881.116 2.717.334M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8.5 9.5q1.625-1.5 3.25 0t3.25 0M15 20q1.625-1.5 3.25 0t3.25 0");
}

</style>

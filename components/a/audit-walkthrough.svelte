<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu-72bbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audit-walkthrough" {...props}></Icon>
<style>
:global(.xu-72bbrm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0m1 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m7-12a2.75 4 0 1 0 5.5 0a2.75 4 0 1 0-5.5 0m1 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>

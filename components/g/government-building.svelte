<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkl52nbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:government-building" {...props}></Icon>
<style>
:global(.nkl52nbwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9a4.5 4.5 0 0 1 9 0M12 2.5v2M3 9h18M3 21h18M6 12v6m4-6v6m4-6v6m4-6v6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx-40ie9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:a-frame-tent" {...props}></Icon>
<style>
:global(.jx-40ie9h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5L13.5 3M21 20.5L10.5 3M3 20.5h18m-12 0l3-6l3 6");
}

</style>

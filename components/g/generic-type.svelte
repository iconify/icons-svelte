<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl31llz7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:generic-type" {...props}></Icon>
<style>
:global(.vl31llz7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 5.5l-5 6.5l5 6.5m9-13l5 6.5l-5 6.5m-7-11h5m-2.5 0V17");
}

</style>

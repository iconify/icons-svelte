<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wifnd3bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:person-pointing" {...props}></Icon>
<style>
:global(.wifnd3bza) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 8v6.5M5 21l3-6.5l3 6.5m-6.5-8L8 9h5.5L20 7");
}

</style>

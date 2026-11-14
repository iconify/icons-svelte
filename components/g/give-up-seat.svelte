<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3vu8g22k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:give-up-seat" {...props}></Icon>
<style>
:global(.i3vu8g22k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.5 3.5l-1 10.5h-7m3.5 0v6.5m-3.5 0h7m-16-13h4v-3l5 5l-5 5v-3h-4Z");
}

</style>

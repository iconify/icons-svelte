<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thb_myb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gonemad" {...props}></Icon>
<style>
:global(.thb_myb4o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25 14.75L8.979 5.5V24zm0 18.5L8.979 24v18.5zM41.022 24L25 14.75v18.5z");
}

</style>

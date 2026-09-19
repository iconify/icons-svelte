<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s06qd4byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:l-speed" {...props}></Icon>
<style>
:global(.s06qd4byw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.79 12.72l21.24 29.06l17.76-12.99l-4.87-6.66l-11.1 8.12l-16.37-22.4Z");
}

</style>

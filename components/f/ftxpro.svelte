<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d3cuaxbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ftxpro" {...props}></Icon>
<style>
:global(.d3cuaxbwa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 28.875H24v9.75h-9.75zm0-19.5H43.5v9.75H14.25zm-9.75 9.75h9.75v9.75H4.5zm9.75 0h19.5v9.75h-19.5z");
}

</style>

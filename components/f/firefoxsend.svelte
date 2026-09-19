<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e--hdhb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:firefoxsend" {...props}></Icon>
<style>
:global(.e--hdhb9o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24.17a18.5 18.5 0 0 0-37 0Zm-18.5 0v18.16m0 0l8.84-8.84m-17.68 0L24 42.33");
}

</style>

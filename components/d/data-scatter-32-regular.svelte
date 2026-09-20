<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zjh_6xbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-scatter-32-regular" {...props}></Icon>
<style>
:global(.zjh_6xbnn) {
  fill: currentColor;
  d: path("M5 4a1 1 0 0 0-2 0v20.5A4.5 4.5 0 0 0 7.5 29H28a1 1 0 1 0 0-2H7.5A2.5 2.5 0 0 1 5 24.5zm7 4a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-2 4a2 2 0 1 1 4 0a2 2 0 0 1-4 0m9-3a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-2a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-3 9a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-2 4a2 2 0 1 1 4 0a2 2 0 0 1-4 0");
}

</style>

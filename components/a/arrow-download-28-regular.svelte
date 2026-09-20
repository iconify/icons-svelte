<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="the2o8bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-download-28-regular" {...props}></Icon>
<style>
:global(.the2o8bju) {
  fill: currentColor;
  d: path("M14.75 3.75a.75.75 0 0 0-1.5 0v14.69l-4.97-4.97a.75.75 0 0 0-1.06 1.06l6.25 6.25a.75.75 0 0 0 1.06 0l6.25-6.25a.75.75 0 1 0-1.06-1.06l-4.97 4.97zm-9 19.75a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5z");
}

</style>

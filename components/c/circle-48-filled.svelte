<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s6tgq0b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-48-filled" {...props}></Icon>
<style>
:global(.s6tgq0b5z) {
  fill: currentColor;
  d: path("M44 24c0 11.046-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4s20 8.954 20 20");
}

</style>

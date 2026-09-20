<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="osvupob-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:grid-dots-28-regular" {...props}></Icon>
<style>
:global(.osvupob-f) {
  fill: currentColor;
  d: path("M5.5 20.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4M5.5 12a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m-17-8.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4m8.5 0a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>

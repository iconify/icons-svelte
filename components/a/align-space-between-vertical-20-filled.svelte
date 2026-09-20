<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tsiqo7b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-space-between-vertical-20-filled" {...props}></Icon>
<style>
:global(.tsiqo7b-c) {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm13 0a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2z");
}

</style>

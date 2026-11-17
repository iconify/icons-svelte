<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9e5l8b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bridge-bulk" {...props}></Icon>
<style>
:global(.l9e5l8b7v) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 5a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-2a3 3 0 1 0-6 0v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3Z");
}

</style>

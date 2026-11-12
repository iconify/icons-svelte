<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7km6i-6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-pause-corner-fill" {...props}></Icon>
<style>
:global(.q7km6i-6r) {
  fill: currentColor;
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1m-4 4v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m4 0v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0");
}

</style>

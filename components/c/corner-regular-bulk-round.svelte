<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z55qg0bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:corner-regular-bulk-round" {...props}></Icon>
<style>
:global(.z55qg0bll) {
  fill: currentColor;
  d: path("M4 12a8 8 0 0 1 8-8h7a1 1 0 0 1 0 2h-7a6 6 0 0 0-6 6v7a1 1 0 0 1-2 0Z");
}

</style>

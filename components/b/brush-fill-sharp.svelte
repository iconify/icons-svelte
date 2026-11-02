<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epyks-d-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brush-fill-sharp" {...props}></Icon>
<style>
:global(.epyks-d-m) {
  fill: currentColor;
  d: path("M9 2v4a1 1 0 0 0 2 0V2h2v4a1 1 0 0 0 2 0V2h3a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-3v4a3 3 0 1 1-6 0v-4H6a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM7 13h3a1 1 0 0 1 1 1v5a1 1 0 0 0 2 0v-5a1 1 0 0 1 1-1h3v-2H7Z");
}

</style>

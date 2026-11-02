<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfbunacni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-d-bulk-sharp" {...props}></Icon>
<style>
:global(.gfbunacni) {
  fill: currentColor;
  d: path("M7 3h5a6 6 0 0 1 6 6v6a6 6 0 0 1-6 6H7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m1 16h4a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4H8Z");
}

</style>

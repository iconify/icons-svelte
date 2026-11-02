<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1t6yb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plus-minus-fill-round" {...props}></Icon>
<style>
:global(.xy1t6yb2g) {
  fill: currentColor;
  d: path("M13 4v5h5a1 1 0 0 1 0 2h-5v5a1 1 0 0 1-2 0v-5H6a1 1 0 0 1 0-2h5V4a1 1 0 0 1 2 0m5 15a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>

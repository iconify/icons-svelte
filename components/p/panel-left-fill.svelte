<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0vgaj6-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-fill" {...props}></Icon>
<style>
:global(.y0vgaj6-n) {
  fill: currentColor;
  d: path("M18 21H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3m-8-2h8a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1h-8Z");
}

</style>

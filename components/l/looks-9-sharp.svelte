<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk34isnok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:looks-9-sharp" {...props}></Icon>
<style>
:global(.vk34isnok) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14V5H5zm0 0V5h14v14zm5.5-2.5h4v-9h-5v5h4v3h-3zm3-5h-3v-3h3z");
}

</style>

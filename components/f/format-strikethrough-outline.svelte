<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9c4kb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-strikethrough-outline" {...props}></Icon>
<style>
:global(.ta9c4kb7d) {
  fill: currentColor;
  d: path("M2 14v-2h20v2zm8.5-4V7H5V4h14v3h-5.5v3zm0 10v-4h3v4z");
}

</style>

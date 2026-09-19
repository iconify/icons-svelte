<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yizktvb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-publish" {...props}></Icon>
<style>
:global(.yizktvb6m) {
  fill: currentColor;
  d: path("M5 4v2h14V4zm0 10h4v6h6v-6h4l-7-7z");
}

</style>

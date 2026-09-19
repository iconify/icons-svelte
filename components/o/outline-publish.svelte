<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1d4aoxgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-publish" {...props}></Icon>
<style>
:global(.k1d4aoxgi) {
  fill: currentColor;
  d: path("M5 4h14v2H5zm0 10h4v6h6v-6h4l-7-7zm8-2v6h-2v-6H9.83L12 9.83L14.17 12z");
}

</style>

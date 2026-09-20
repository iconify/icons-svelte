<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xgpjwtxkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-four-thin" {...props}></Icon>
<style>
:global(.xgpjwtxkl) {
  fill: currentColor;
  d: path("M184 164h-20V48a4 4 0 0 0-7.12-2.5l-96 120A4 4 0 0 0 64 172h92v36a4 4 0 0 0 8 0v-36h20a4 4 0 0 0 0-8m-28 0H72.32L156 59.4Z");
}

</style>

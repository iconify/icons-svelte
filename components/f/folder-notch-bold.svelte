<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jn7d_4b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:folder-notch-bold" {...props}></Icon>
<style>
:global(.jn7d_4b5o) {
  fill: currentColor;
  d: path("M216 68h-84l-26.67-20a20.12 20.12 0 0 0-12-4H40a20 20 0 0 0-20 20v136a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V88a20 20 0 0 0-20-20M44 68h48l16 12l-16 12H44Zm168 128H44v-80h49.33a20.12 20.12 0 0 0 12-4L132 92h80Z");
}

</style>

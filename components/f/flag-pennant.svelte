<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="twwjynbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:flag-pennant" {...props}></Icon>
<style>
:global(.twwjynbmy) {
  fill: currentColor;
  d: path("m242.63 96.44l-184-64A8 8 0 0 0 48 40v176a8 8 0 0 0 16 0v-42.31l178.63-62.13a8 8 0 0 0 0-15.12M64 156.75V51.25L215.65 104Z");
}

</style>

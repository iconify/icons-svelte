<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sw-b7vbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:map-pin-simple-fill" {...props}></Icon>
<style>
:global(.sw-b7vbpv) {
  fill: currentColor;
  d: path("M136 127.42V232a8 8 0 0 1-16 0V127.42a56 56 0 1 1 16 0");
}

</style>

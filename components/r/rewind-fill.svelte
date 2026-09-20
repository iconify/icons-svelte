<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dnmlfgb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:rewind-fill" {...props}></Icon>
<style>
:global(.dnmlfgb5a) {
  fill: currentColor;
  d: path("M232 71.84v112.32a15.92 15.92 0 0 1-24.48 13.34L128 146.86v37.3a15.92 15.92 0 0 1-24.48 13.34l-88.19-56.16a15.8 15.8 0 0 1 0-26.68l88.19-56.16A15.91 15.91 0 0 1 128 71.84v37.3l79.52-50.64A15.91 15.91 0 0 1 232 71.84");
}

</style>

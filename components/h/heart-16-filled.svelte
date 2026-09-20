<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mcb5r-f4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:heart-16-filled" {...props}></Icon>
<style>
:global(.mcb5r-f4t) {
  fill: currentColor;
  d: path("M7.541 3.948a3.25 3.25 0 0 0-4.595-.012a3.25 3.25 0 0 0 .012 4.595l4.707 4.708a.5.5 0 0 0 .707 0l4.683-4.68a3.25 3.25 0 0 0-.012-4.594a3.25 3.25 0 0 0-4.601-.012l-.447.448z");
}

</style>

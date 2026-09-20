<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="em0c6r5qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-20-regular" {...props}></Icon>
<style>
:global(.em0c6r5qn) {
  fill: currentColor;
  d: path("M2 10a6 6 0 0 1 6-6h4a6 6 0 0 1 0 12H8a6 6 0 0 1-6-6m6-5a5 5 0 0 0 0 10h4a5 5 0 0 0 0-10z");
}

</style>

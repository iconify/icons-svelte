<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hawdhbufd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-16-filled" {...props}></Icon>
<style>
:global(.hawdhbufd) {
  fill: currentColor;
  d: path("M1 8a5 5 0 0 1 5-5h4a5 5 0 0 1 0 10H6a5 5 0 0 1-5-5");
}

</style>

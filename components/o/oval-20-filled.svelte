<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r3h4cab2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-20-filled" {...props}></Icon>
<style>
:global(.r3h4cab2u) {
  fill: currentColor;
  d: path("M2 10a6 6 0 0 1 6-6h4a6 6 0 0 1 0 12H8a6 6 0 0 1-6-6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ck9teebse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-bidirectional-left-right-28-regular" {...props}></Icon>
<style>
:global(.ck9teebse) {
  fill: currentColor;
  d: path("M10.28 7.22a.75.75 0 0 1 0 1.06L5.56 13h16.88l-4.72-4.72a.75.75 0 0 1 1.06-1.06l6 6a.75.75 0 0 1 0 1.06l-6 6a.75.75 0 1 1-1.06-1.06l4.72-4.72H5.56l4.72 4.72a.75.75 0 1 1-1.06 1.06l-6-6a.75.75 0 0 1 0-1.06l6-6a.75.75 0 0 1 1.06 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yhikcccxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-down-12-filled" {...props}></Icon>
<style>
:global(.yhikcccxf) {
  fill: currentColor;
  d: path("M3.076 4.617A1 1 0 0 1 4 4h4a1 1 0 0 1 .707 1.707l-2 2a1 1 0 0 1-1.414 0l-2-2a1 1 0 0 1-.217-1.09");
}

</style>

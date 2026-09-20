<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn2ojm-wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-circle-left-20-filled" {...props}></Icon>
<style>
:global(.mn2ojm-wy) {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m1.854 4.854a.5.5 0 0 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L8.707 10z");
}

</style>

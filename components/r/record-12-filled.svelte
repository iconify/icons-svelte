<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cgpsgj6_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-12-filled" {...props}></Icon>
<style>
:global(.cgpsgj6_f) {
  fill: currentColor;
  d: path("M6 11A5 5 0 1 0 6 1a5 5 0 0 0 0 10m0-2a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

</style>

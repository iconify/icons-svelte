<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sfm1dmb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-stop-48-filled" {...props}></Icon>
<style>
:global(.sfm1dmb8r) {
  fill: currentColor;
  d: path("M44 24c0 11.046-8.954 20-20 20S4 35.046 4 24S12.954 4 24 4s20 8.954 20 20m-27-9a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V17a2 2 0 0 0-2-2z");
}

</style>

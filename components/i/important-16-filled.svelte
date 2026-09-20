<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="irzpsnb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:important-16-filled" {...props}></Icon>
<style>
:global(.irzpsnb-n) {
  fill: currentColor;
  d: path("M5.96 4.457a2.075 2.075 0 1 1 4.08 0l-.856 4.56a1.205 1.205 0 0 1-2.368 0zM9.5 12.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="durhuiblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-2-dashes-solid-16-regular" {...props}></Icon>
<style>
:global(.durhuiblv) {
  fill: currentColor;
  d: path("M2.5 5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM7 5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm4.5 0a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm-9 5a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>

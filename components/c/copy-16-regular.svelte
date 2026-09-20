<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pj61nbbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:copy-16-regular" {...props}></Icon>
<style>
:global(.pj61nbbgm) {
  fill: currentColor;
  d: path("M5 6H4a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1h1a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h1zm7-4a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zM8 3a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V4a1 1 0 0 0-1-1z");
}

</style>

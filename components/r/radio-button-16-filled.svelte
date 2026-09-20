<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u324b8e7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:radio-button-16-filled" {...props}></Icon>
<style>
:global(.u324b8e7h) {
  fill: currentColor;
  d: path("M8 11a3 3 0 1 0 0-6a3 3 0 0 0 0 6m0-9a6 6 0 1 0 0 12A6 6 0 0 0 8 2M3 8a5 5 0 1 1 10 0A5 5 0 0 1 3 8");
}

</style>

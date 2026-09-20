<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z2gqeccjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:brackets-square-light" {...props}></Icon>
<style>
:global(.z2gqeccjf) {
  fill: currentColor;
  d: path("M46 46v164h34a6 6 0 0 1 0 12H40a6 6 0 0 1-6-6V40a6 6 0 0 1 6-6h40a6 6 0 0 1 0 12Zm170-12h-40a6 6 0 0 0 0 12h34v164h-34a6 6 0 0 0 0 12h40a6 6 0 0 0 6-6V40a6 6 0 0 0-6-6");
}

</style>

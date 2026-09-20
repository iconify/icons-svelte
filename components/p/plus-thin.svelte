<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qdvd0cb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:plus-thin" {...props}></Icon>
<style>
:global(.qdvd0cb9g) {
  fill: currentColor;
  d: path("M220 128a4 4 0 0 1-4 4h-84v84a4 4 0 0 1-8 0v-84H40a4 4 0 0 1 0-8h84V40a4 4 0 0 1 8 0v84h84a4 4 0 0 1 4 4");
}

</style>

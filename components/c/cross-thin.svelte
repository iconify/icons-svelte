<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yzvn5pdok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cross-thin" {...props}></Icon>
<style>
:global(.yzvn5pdok) {
  fill: currentColor;
  d: path("M200 76h-44V32a12 12 0 0 0-12-12h-32a12 12 0 0 0-12 12v44H56a12 12 0 0 0-12 12v32a12 12 0 0 0 12 12h44v92a12 12 0 0 0 12 12h32a12 12 0 0 0 12-12v-92h44a12 12 0 0 0 12-12V88a12 12 0 0 0-12-12m4 44a4 4 0 0 1-4 4h-48a4 4 0 0 0-4 4v96a4 4 0 0 1-4 4h-32a4 4 0 0 1-4-4v-96a4 4 0 0 0-4-4H56a4 4 0 0 1-4-4V88a4 4 0 0 1 4-4h48a4 4 0 0 0 4-4V32a4 4 0 0 1 4-4h32a4 4 0 0 1 4 4v48a4 4 0 0 0 4 4h48a4 4 0 0 1 4 4Z");
}

</style>

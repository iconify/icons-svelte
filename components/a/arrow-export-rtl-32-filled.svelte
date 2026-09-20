<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rg8n9cc3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-rtl-32-filled" {...props}></Icon>
<style>
:global(.rg8n9cc3i) {
  fill: currentColor;
  d: path("M28.75 4.5c.69 0 1.25.56 1.25 1.25v20a1.25 1.25 0 0 1-2.5 0v-20c0-.69.56-1.25 1.25-1.25M9.866 7.366a1.25 1.25 0 1 1 1.768 1.768L6.268 14.5H23.75a1.25 1.25 0 0 1 0 2.5H6.268l5.366 5.366a1.25 1.25 0 0 1-1.768 1.768l-7.5-7.5a1.25 1.25 0 0 1 0-1.768z");
}

</style>

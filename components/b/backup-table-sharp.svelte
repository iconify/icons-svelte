<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfd0q4bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:backup-table-sharp" {...props}></Icon>
<style>
:global(.wfd0q4bwf) {
  fill: currentColor;
  d: path("M8 16h5v-5H8zm0-7h12V4H8zm7 7h5v-5h-5zm-9 2V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>

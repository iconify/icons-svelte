<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqtqs-bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cable-fill" {...props}></Icon>
<style>
:global(.rqtqs-bta) {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1.171A3.001 3.001 0 0 1 9 10H8a.997.997 0 0 0 1 1h6a3 3 0 0 1 3 3h1a3 3 0 0 1 1 5.829V21a1 1 0 0 1-2 0v-1h-2v1a1 1 0 0 1-2 0v-1.171A3.001 3.001 0 0 1 15 14h1a.997.997 0 0 0-1-1H9a3 3 0 0 1-3-3H5a3 3 0 0 1-1-5.829Z");
}

</style>

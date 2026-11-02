<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv891-qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-r-fill" {...props}></Icon>
<style>
:global(.jiv891-qv) {
  fill: currentColor;
  d: path("M6 12V4a1 1 0 0 1 1-1h6a5 5 0 0 1 1.503 9.77l3.391 6.783a1 1 0 1 1-1.788.894L12.382 13H8v7a1 1 0 0 1-2 0Zm2-1h5a3 3 0 1 0 0-6H8Z");
}

</style>

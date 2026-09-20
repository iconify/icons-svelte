<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_uphxbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:reorder-outline" {...props}></Icon>
<style>
:global(.h_uphxbgj) {
  fill: currentColor;
  d: path("M4 18v-1h16v1zm0-3.673v-1h16v1zm0-3.654v-1h16v1zM4 7V6h16v1z");
}

</style>

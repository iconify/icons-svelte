<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iivqedcba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:responsive-layout-outline-sharp" {...props}></Icon>
<style>
:global(.iivqedcba) {
  fill: currentColor;
  d: path("M4 20V9h5V4h11v16zm11-1h4V5h-9v4h5zm-5 0h4v-9h-4zm-5 0h4v-9H5zM15 9v1zm0 0");
}

</style>

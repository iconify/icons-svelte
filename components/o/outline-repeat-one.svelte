<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf8ph6q3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-repeat-one" {...props}></Icon>
<style>
:global(.cf8ph6q3o) {
  fill: currentColor;
  d: path("M7 7h10v3l4-4l-4-4v3H5v6h2zm10 10H7v-3l-4 4l4 4v-3h12v-6h-2zm-4-2V9h-1l-2 1v1h1.5v4z");
}

</style>

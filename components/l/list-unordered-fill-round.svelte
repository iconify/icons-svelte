<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5v2fb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-unordered-fill-round" {...props}></Icon>
<style>
:global(.x-5v2fb5a) {
  fill: currentColor;
  d: path("M5 6h.01a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m4 0h10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m-4 5h.01a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m4 0h10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m-4 5h.01a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m4 0h10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>

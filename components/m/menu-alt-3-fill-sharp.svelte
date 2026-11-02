<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahowc3_6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-3-fill-sharp" {...props}></Icon>
<style>
:global(.ahowc3_6y) {
  fill: currentColor;
  d: path("M13 6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm6 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm-6 5a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>

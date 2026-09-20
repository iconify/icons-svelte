<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="pv8w07f6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-header-footer-28-filled" {...props}></Icon>
<style>
:global(.pv8w07f6o) {
  fill: currentColor;
  d: path("M21.25 2A2.75 2.75 0 0 1 24 4.75v18.5A2.75 2.75 0 0 1 21.25 26H6.75A2.75 2.75 0 0 1 4 23.25V4.75A2.75 2.75 0 0 1 6.75 2zM9 19a1.5 1.5 0 0 0 0 3h10a1.5 1.5 0 0 0 0-3zM9 6a1.5 1.5 0 1 0 0 3h10a1.5 1.5 0 0 0 0-3z");
}

</style>

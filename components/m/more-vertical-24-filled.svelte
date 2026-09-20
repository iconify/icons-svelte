<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w40n5i41d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-vertical-24-filled" {...props}></Icon>
<style>
:global(.w40n5i41d) {
  fill: currentColor;
  d: path("M12 8a2 2 0 1 1 0-4a2 2 0 0 1 0 4m0 6a2 2 0 1 1 0-4a2 2 0 0 1 0 4m-2 4a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="zkuatjb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pause-28-regular" {...props}></Icon>
<style>
:global(.zkuatjb7r) {
  fill: currentColor;
  d: path("M6.75 3A2.75 2.75 0 0 0 4 5.75v16.5A2.75 2.75 0 0 0 6.75 25h3a2.75 2.75 0 0 0 2.75-2.75V5.75A2.75 2.75 0 0 0 9.75 3zM5.5 5.75c0-.69.56-1.25 1.25-1.25h3c.69 0 1.25.56 1.25 1.25v16.5c0 .69-.56 1.25-1.25 1.25h-3c-.69 0-1.25-.56-1.25-1.25zM18.25 3a2.75 2.75 0 0 0-2.75 2.75v16.5A2.75 2.75 0 0 0 18.25 25h3A2.75 2.75 0 0 0 24 22.25V5.75A2.75 2.75 0 0 0 21.25 3zM17 5.75c0-.69.56-1.25 1.25-1.25h3c.69 0 1.25.56 1.25 1.25v16.5c0 .69-.56 1.25-1.25 1.25h-3c-.69 0-1.25-.56-1.25-1.25z");
}

</style>

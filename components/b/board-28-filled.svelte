<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="a50rukbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:board-28-filled" {...props}></Icon>
<style>
:global(.a50rukbmh) {
  fill: currentColor;
  d: path("M13.5 3v6.5H3V6.75A3.75 3.75 0 0 1 6.75 3zM15 3v13.5h10V6.75A3.75 3.75 0 0 0 21.25 3zm10 15H15v7h6.25A3.75 3.75 0 0 0 25 21.25zm-11.5 7V11H3v10.25A3.75 3.75 0 0 0 6.75 25z");
}

</style>

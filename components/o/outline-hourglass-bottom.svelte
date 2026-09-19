<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkmrd3b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-hourglass-bottom" {...props}></Icon>
<style>
:global(.gkmrd3b5u) {
  fill: currentColor;
  d: path("m18 22l-.01-6L14 12l3.99-4.01L18 2H6v6l4 4l-4 3.99V22zM8 7.5V4h8v3.5l-4 4z");
}

</style>

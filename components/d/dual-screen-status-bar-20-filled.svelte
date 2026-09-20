<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="js9ta0b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dual-screen-status-bar-20-filled" {...props}></Icon>
<style>
:global(.js9ta0b3o) {
  fill: currentColor;
  d: path("M16 16h-5.5V4H16a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2M4 4h5.5v12H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m8.5 2a.5.5 0 0 0 0 1H16a.5.5 0 0 0 0-1z");
}

</style>

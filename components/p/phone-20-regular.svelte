<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ablfi8dpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:phone-20-regular" {...props}></Icon>
<style>
:global(.ablfi8dpb) {
  fill: currentColor;
  d: path("M9 14a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM7 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zM6 4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1z");
}

</style>

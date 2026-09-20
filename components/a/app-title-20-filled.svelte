<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dac8vpb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:app-title-20-filled" {...props}></Icon>
<style>
:global(.dac8vpb2t) {
  fill: currentColor;
  d: path("M7 3a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h6a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zM4.5 17a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>

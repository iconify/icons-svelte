<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f21ig-h_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:keyboard-arrow-down" {...props}></Icon>
<style>
:global(.f21ig-h_x) {
  fill: currentColor;
  d: path("M7.41 8.59L12 13.17l4.59-4.58L18 10l-6 6l-6-6z");
}

</style>

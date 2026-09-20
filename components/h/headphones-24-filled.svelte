<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrh6mwbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:headphones-24-filled" {...props}></Icon>
<style>
:global(.lrh6mwbly) {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10v7a3 3 0 0 1-3 3h-3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h4.5v-2a8.5 8.5 0 0 0-17 0v2H8a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3v-7C2 6.477 6.477 2 12 2");
}

</style>

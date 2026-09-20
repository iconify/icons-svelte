<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxj-t0b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-24-filled" {...props}></Icon>
<style>
:global(.oxj-t0b0a) {
  fill: currentColor;
  d: path("M2 12a8 8 0 0 1 8-8h4a8 8 0 1 1 0 16h-4a8 8 0 0 1-8-8");
}

</style>

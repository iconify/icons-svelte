<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsdtt4zez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-24-regular" {...props}></Icon>
<style>
:global(.gsdtt4zez) {
  fill: currentColor;
  d: path("M4.53 12.97a.75.75 0 0 0-1.06 1.06l4.5 4.5a.75.75 0 0 0 1.06 0l11-11a.75.75 0 0 0-1.06-1.06L8.5 16.94z");
}

</style>

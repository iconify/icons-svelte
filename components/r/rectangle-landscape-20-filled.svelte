<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p6c9j-17z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-landscape-20-filled" {...props}></Icon>
<style>
:global(.p6c9j-17z) {
  fill: currentColor;
  d: path("M5 4a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3z");
}

</style>

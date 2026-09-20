<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="sm1twrbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:oval-28-filled" {...props}></Icon>
<style>
:global(.sm1twrbdt) {
  fill: currentColor;
  d: path("M2 14a9 9 0 0 1 9-9h6a9 9 0 1 1 0 18h-6a9 9 0 0 1-9-9");
}

</style>

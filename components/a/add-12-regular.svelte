<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i3tlxabem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-12-regular" {...props}></Icon>
<style>
:global(.i3tlxabem) {
  fill: currentColor;
  d: path("M6 2a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 6 2");
}

</style>

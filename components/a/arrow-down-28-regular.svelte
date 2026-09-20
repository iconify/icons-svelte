<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="msmzisuhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-28-regular" {...props}></Icon>
<style>
:global(.msmzisuhd) {
  fill: currentColor;
  d: path("M23.792 15.267a.75.75 0 1 0-1.082-1.04L14.752 22.5V3.748a.75.75 0 0 0-1.5 0V22.5l-7.959-8.273a.75.75 0 0 0-1.08 1.04l9.069 9.428a1 1 0 0 0 1.441 0z");
}

</style>

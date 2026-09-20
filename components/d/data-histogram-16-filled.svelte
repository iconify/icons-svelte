<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kzmq18k0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-histogram-16-filled" {...props}></Icon>
<style>
:global(.kzmq18k0i) {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0-4 0v10h4zM5 7H4a2 2 0 0 0-2 2v4.5a.5.5 0 0 0 .5.5H5zm6 7h2.5a.5.5 0 0 0 .5-.5V7a2 2 0 0 0-2-2h-1z");
}

</style>

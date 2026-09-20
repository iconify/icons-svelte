<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tx-0mjalx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:grid-dots-16-regular" {...props}></Icon>
<style>
:global(.tx-0mjalx) {
  fill: currentColor;
  d: path("M3 12a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2M3 7a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2M3 2a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2m5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2");
}

</style>

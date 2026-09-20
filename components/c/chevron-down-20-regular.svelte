<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ow92nzbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-20-regular" {...props}></Icon>
<style>
:global(.ow92nzbyx) {
  fill: currentColor;
  d: path("M15.854 7.646a.5.5 0 0 1 .001.707l-5.465 5.484a.55.55 0 0 1-.78 0L4.147 8.353a.5.5 0 1 1 .708-.706L10 12.812l5.147-5.165a.5.5 0 0 1 .707-.001");
}

</style>

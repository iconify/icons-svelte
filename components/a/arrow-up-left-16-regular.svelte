<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yg05dsbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-left-16-regular" {...props}></Icon>
<style>
:global(.yg05dsbxz) {
  fill: currentColor;
  d: path("M8.5 3a.5.5 0 0 0 0-1h-6a.5.5 0 0 0-.5.5v6a.5.5 0 0 0 1 0V3.707l10.147 10.147a.5.5 0 0 0 .707-.708L3.707 3z");
}

</style>

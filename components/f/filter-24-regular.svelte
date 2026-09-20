<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmc3hfymh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:filter-24-regular" {...props}></Icon>
<style>
:global(.tmc3hfymh) {
  fill: currentColor;
  d: path("M13.5 16a.75.75 0 0 1 0 1.5h-3a.75.75 0 0 1 0-1.5zm3-5a.75.75 0 0 1 0 1.5h-9a.75.75 0 0 1 0-1.5zm3-5a.75.75 0 0 1 0 1.5h-15a.75.75 0 0 1 0-1.5z");
}

</style>

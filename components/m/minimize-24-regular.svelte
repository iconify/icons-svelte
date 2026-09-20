<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g1u4hjsvy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:minimize-24-regular" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g1u4hjsvy) {
  d: path("M3.755 12.5h16.492a.75.75 0 1 0 0-1.5H3.755a.75.75 0 0 0 0 1.5z");
  fill: currentColor;
}

</style>

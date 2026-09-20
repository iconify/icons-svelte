<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z29_f9aab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-dash-dot-dash-20-filled" {...props}></Icon>
<style>
:global(.z29_f9aab) {
  fill: currentColor;
  d: path("M10 11.75a1.75 1.75 0 1 0 0-3.5a1.75 1.75 0 0 0 0 3.5M2.75 9a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zm12 0a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5z");
}

</style>

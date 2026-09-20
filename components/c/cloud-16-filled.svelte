<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t8sdbab6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:cloud-16-filled" {...props}></Icon>
<style>
:global(.t8sdbab6k) {
  fill: currentColor;
  d: path("M4.03 5.507a4 4 0 0 1 7.94 0A3.25 3.25 0 0 1 11.75 12h-7.5a3.25 3.25 0 0 1-.22-6.493");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ybyetyblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:column-single-16-regular" {...props}></Icon>
<style>
:global(.ybyetyblk) {
  fill: currentColor;
  d: path("M5.75 2A1.75 1.75 0 0 0 4 3.75v8.5c0 .966.784 1.75 1.75 1.75h3.5A1.75 1.75 0 0 0 11 12.25v-8.5A1.75 1.75 0 0 0 9.25 2zM5 3.75A.75.75 0 0 1 5.75 3h3.5a.75.75 0 0 1 .75.75V5H5zM5 6h5v6.25a.75.75 0 0 1-.75.75h-3.5a.75.75 0 0 1-.75-.75z");
}

</style>

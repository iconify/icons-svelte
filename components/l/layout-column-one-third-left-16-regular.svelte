<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rta4xd35z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-one-third-left-16-regular" {...props}></Icon>
<style>
:global(.rta4xd35z) {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 4.5A1.5 1.5 0 0 1 4.5 3h1v10h-1A1.5 1.5 0 0 1 3 11.5zM6.5 13V3h5A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5z");
}

</style>

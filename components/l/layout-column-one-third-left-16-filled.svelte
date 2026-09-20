<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hezqkzbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-one-third-left-16-filled" {...props}></Icon>
<style>
:global(.hezqkzbyw) {
  fill: currentColor;
  d: path("M6 14h5.5a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2H6zM5 2h-.5A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14H5z");
}

</style>

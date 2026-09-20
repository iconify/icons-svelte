<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ie5xp722a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-three-focus-bottom-16-filled" {...props}></Icon>
<style>
:global(.ie5xp722a) {
  fill: currentColor;
  d: path("M4.5 14A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5zM13 7H3v3h10zm0-1V4.5A1.5 1.5 0 0 0 11.5 3h-7A1.5 1.5 0 0 0 3 4.5V6z");
}

</style>

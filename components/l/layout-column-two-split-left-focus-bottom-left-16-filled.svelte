<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="of9ayv1-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-two-split-left-focus-bottom-left-16-filled" {...props}></Icon>
<style>
:global(.of9ayv1-e) {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM4.5 3A1.5 1.5 0 0 0 3 4.5V8h4.5V3zm4 0v10h3a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 11.5 3z");
}

</style>

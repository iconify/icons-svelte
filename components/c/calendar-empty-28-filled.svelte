<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="iu0i_1hda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-empty-28-filled" {...props}></Icon>
<style>
:global(.iu0i_1hda) {
  fill: currentColor;
  d: path("M25 9.5v12.25A3.25 3.25 0 0 1 21.75 25H6.25A3.25 3.25 0 0 1 3 21.75V9.5zM21.75 3A3.25 3.25 0 0 1 25 6.25V8H3V6.25A3.25 3.25 0 0 1 6.25 3z");
}

</style>

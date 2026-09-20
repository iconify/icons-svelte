<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov258qapc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-landscape-16-filled" {...props}></Icon>
<style>
:global(.ov258qapc) {
  fill: currentColor;
  d: path("M3.5 3A2.5 2.5 0 0 0 1 5.5v5A2.5 2.5 0 0 0 3.5 13h9a2.5 2.5 0 0 0 2.5-2.5v-5A2.5 2.5 0 0 0 12.5 3z");
}

</style>

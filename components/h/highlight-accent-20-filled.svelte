<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o4d4-6bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:highlight-accent-20-filled" {...props}></Icon>
<style>
:global(.o4d4-6bgs) {
  fill: currentColor;
  d: path("M16.5 3v4a.5.5 0 0 1-.5.5H4a.5.5 0 0 1-.5-.5V3zm-10 7.5v7l6.447-3.106a1 1 0 0 0 .553-.894v-3z");
}

</style>

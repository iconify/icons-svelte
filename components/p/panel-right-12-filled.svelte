<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zcu4_y75g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-right-12-filled" {...props}></Icon>
<style>
:global(.zcu4_y75g) {
  fill: currentColor;
  d: path("M9 2H3a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2M2 8V4a1 1 0 0 1 1-1h4v6H3a1 1 0 0 1-1-1");
}

</style>

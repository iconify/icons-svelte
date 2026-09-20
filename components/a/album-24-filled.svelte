<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqlm60gss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:album-24-filled" {...props}></Icon>
<style>
:global(.gqlm60gss) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2-2h1v16H4a2 2 0 0 1-2-2zm14 2.5h-4a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V9a.5.5 0 0 0-.5-.5M6.5 20H20a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H6.5zM12 7h4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2");
}

</style>

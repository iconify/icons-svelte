<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5qj_bo_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:comment-bank-outline-sharp" {...props}></Icon>
<style>
:global(.y5qj_bo_c) {
  fill: currentColor;
  d: path("M12.5 11V4H4v13.125L5.15 16H20V4h-2.5v7L15 9.5zM2 22V2h20v16H6zM4 4v12z");
}

</style>

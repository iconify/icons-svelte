<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx9rvkkeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dashboard-customize" {...props}></Icon>
<style>
:global(.yx9rvkkeq) {
  fill: currentColor;
  d: path("M3 3h8v8H3zm10 0h8v8h-8zM3 13h8v8H3zm13 0h2v3h3v2h-3v3h-2v-3h-3v-2h3z");
}

</style>

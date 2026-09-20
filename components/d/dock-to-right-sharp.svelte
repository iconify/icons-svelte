<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovl4ztbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:dock-to-right-sharp" {...props}></Icon>
<style>
:global(.ovl4ztbsc) {
  fill: currentColor;
  d: path("M10 19h9V5h-9zm-7 2V3h18v18z");
}

</style>

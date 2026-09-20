<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r05oa340q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dock-to-right-outline-sharp" {...props}></Icon>
<style>
:global(.r05oa340q) {
  fill: currentColor;
  d: path("M5 19h3V5H5zm4 0h10V5H9zm-1 0H5zm-4 1V4h16v16z");
}

</style>

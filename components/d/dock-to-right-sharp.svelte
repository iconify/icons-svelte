<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miqrinbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:dock-to-right-sharp" {...props}></Icon>
<style>
:global(.miqrinbch) {
  fill: currentColor;
  d: path("M9 19h10V5H9zm-5 1V4h16v16z");
}

</style>

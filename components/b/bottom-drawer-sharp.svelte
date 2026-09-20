<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk3obybxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-drawer-sharp" {...props}></Icon>
<style>
:global(.yk3obybxt) {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 5v9.096L6.596 12.5h10.808L19 14.096V5z");
}

</style>

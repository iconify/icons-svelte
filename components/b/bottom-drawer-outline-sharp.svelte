<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhgxqrb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-drawer-outline-sharp" {...props}></Icon>
<style>
:global(.vhgxqrb8e) {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 5v9.096L6.596 12.5h10.808L19 14.096V5zm0 14h14v-3.5l-2-2H7l-2 2zm0 0h14z");
}

</style>

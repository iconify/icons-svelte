<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tplyylhww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-menu-close-rounded" {...props}></Icon>
<style>
:global(.tplyylhww) {
  fill: currentColor;
  d: path("M10.15 16.15L6.7 12.7q-.3-.3-.3-.7t.3-.7l3.45-3.45q.25-.25.55-.125t.3.475v7.6q0 .35-.3.475t-.55-.125M13 20V4q0-.425.288-.712T14 3t.713.288T15 4v16q0 .425-.288.713T14 21t-.712-.288T13 20");
}

</style>

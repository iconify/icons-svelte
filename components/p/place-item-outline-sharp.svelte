<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj0ryhbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:place-item-outline-sharp" {...props}></Icon>
<style>
:global(.aj0ryhbik) {
  fill: currentColor;
  d: path("M4 20V8h4.73v1H5v10h14V9h-3.73V8H20v12zm8-4.692L8.692 12l.708-.708l2.1 2.095V1.5h1v11.887l2.1-2.095l.708.708z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmd74ubuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-1-sharp" {...props}></Icon>
<style>
:global(.pmd74ubuk) {
  fill: currentColor;
  d: path("M14 14.5h1v-9h-3v1h2zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>

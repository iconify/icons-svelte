<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij-nmqbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:delete-sweep-outline" {...props}></Icon>
<style>
:global(.ij-nmqbkx) {
  fill: currentColor;
  d: path("M15 18v-2h4v2zm0-8V8h7v2zm0 4v-2h6v2zM3 8H2V6h4V4.5h4V6h4v2h-1v9q0 .825-.587 1.413T11 19H5q-.825 0-1.412-.587T3 17zm2 0v9h6V8zm0 0v9z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="php1gybtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-3-sharp" {...props}></Icon>
<style>
:global(.php1gybtd) {
  fill: currentColor;
  d: path("M11 14.5h5v-9h-5v1h4v3h-2.384v1H15v3h-4zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5yym7oge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-2-sharp" {...props}></Icon>
<style>
:global(.b5yym7oge) {
  fill: currentColor;
  d: path("M11 14.5h5v-1h-4v-3h4v-5h-5v1h4v3h-4zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>

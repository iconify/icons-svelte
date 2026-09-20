<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq4b7sb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:filter-9-sharp" {...props}></Icon>
<style>
:global(.iq4b7sb4f) {
  fill: currentColor;
  d: path("M12 14.5h4v-9h-5v5h4v3h-3zm3-5h-3v-3h3zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>

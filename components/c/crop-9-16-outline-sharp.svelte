<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1sr06b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-9-16-outline-sharp" {...props}></Icon>
<style>
:global(.m1sr06b6h) {
  fill: currentColor;
  d: path("M8 20V4h8v16zM9 5v14h6V5zm0 14V5z");
}

</style>

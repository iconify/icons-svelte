<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_nf5wbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:grid-layout-side-sharp" {...props}></Icon>
<style>
:global(.g_nf5wbbo) {
  fill: currentColor;
  d: path("M20 20V4zM4 20h9.5V4H4zm16 0V4h-5.5v16z");
}

</style>

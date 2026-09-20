<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgv21k0-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:pergola-sharp" {...props}></Icon>
<style>
:global(.dgv21k0-k) {
  fill: currentColor;
  d: path("M4 20V3h1v2h14V3h1v17h-1V9.77H5V20zm7.5 0v-2.827H8.673v-1h6.635v1H12.5V20z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx_2-m0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:kitchen-sharp" {...props}></Icon>
<style>
:global(.qx_2-m0zn) {
  fill: currentColor;
  d: path("M8 8h2V5H8zm0 9h2v-5H8zm-4 5V11h16v11zM4 9V2h16v7z");
}

</style>

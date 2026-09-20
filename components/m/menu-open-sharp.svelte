<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gx02ggfog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:menu-open-sharp" {...props}></Icon>
<style>
:global(.gx02ggfog) {
  fill: currentColor;
  d: path("M3 18v-2h13v2zm16.6-1l-5-5l5-5L21 8.4L17.4 12l3.6 3.6zM3 13v-2h10v2zm0-5V6h13v2z");
}

</style>

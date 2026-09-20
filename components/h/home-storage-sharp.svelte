<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy2ezbbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:home-storage-sharp" {...props}></Icon>
<style>
:global(.dy2ezbbqh) {
  fill: currentColor;
  d: path("M5 21L3 9h18l-2 12zm4-6h6v-2H9zM5 8V6h14v2zm2-3V3h10v2z");
}

</style>

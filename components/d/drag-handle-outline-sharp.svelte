<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8jm_xmse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:drag-handle-outline-sharp" {...props}></Icon>
<style>
:global(.y8jm_xmse) {
  fill: currentColor;
  d: path("M5 14.5v-1h14v1zm0-4v-1h14v1z");
}

</style>

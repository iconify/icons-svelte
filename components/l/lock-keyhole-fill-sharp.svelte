<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhdcdbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-keyhole-fill-sharp" {...props}></Icon>
<style>
:global(.zyhdcdbmp) {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0v3h4a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1Zm6-3a2 2 0 1 0-4 0v3h4Zm-3 9.733V18a1 1 0 0 0 2 0v-2.267a2.001 2.001 0 1 0-2 0");
}

</style>

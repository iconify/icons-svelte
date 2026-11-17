<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vap8yebch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inverter-fill-sharp" {...props}></Icon>
<style>
:global(.vap8yebch) {
  fill: currentColor;
  d: path("M3 3a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm4 8a1 1 0 0 0 .2.6a6 6 0 0 0 9.6 0a1 1 0 0 0 .2-.6V7a1 1 0 0 0-1-1H8a1 1 0 0 0-1 1Zm8 5H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>

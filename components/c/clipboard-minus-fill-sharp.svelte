<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykpe8kbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-minus-fill-sharp" {...props}></Icon>
<style>
:global(.ykpe8kbws) {
  fill: currentColor;
  d: path("M8 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v1h3a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3Zm0 3H6v14h12V6h-2v1a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Zm1 7h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>

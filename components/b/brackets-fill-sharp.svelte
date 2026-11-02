<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yie9aac_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-fill-sharp" {...props}></Icon>
<style>
:global(.yie9aac_c) {
  fill: currentColor;
  d: path("M5 8v8h2a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2Zm15-2a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2V8h-2a1 1 0 0 1 0-2Z");
}

</style>

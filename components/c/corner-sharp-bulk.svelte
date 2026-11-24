<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx48rybny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:corner-sharp-bulk" {...props}></Icon>
<style>
:global(.qx48rybny) {
  fill: currentColor;
  d: path("M4 5a1 1 0 0 1 1-1h14a1 1 0 0 1 0 2H6v13a1 1 0 0 1-2 0Z");
}

</style>

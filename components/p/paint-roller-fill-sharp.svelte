<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2fezubjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-roller-fill-sharp" {...props}></Icon>
<style>
:global(.y2fezubjl) {
  fill: currentColor;
  d: path("M17 2a1 1 0 0 1 1 1v2h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-8v1h1a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h1v-2a1 1 0 0 1 1-1h8V7h-2v2a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>

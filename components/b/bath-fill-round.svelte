<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1ylbb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bath-fill-round" {...props}></Icon>
<style>
:global(.fj1ylbb8f) {
  fill: currentColor;
  d: path("M4 6a3 3 0 1 1 6 0a1 1 0 0 1-2 0a1.001 1.001 0 0 0-2 0v5h15a1 1 0 0 1 0 2h-1v3a3 3 0 0 1-3 3v1a1 1 0 0 1-2 0v-1H9v1a1 1 0 0 1-2 0v-1a3 3 0 0 1-3-3v-3H3a1 1 0 0 1 0-2h1Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_weskb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-branch-fill-round" {...props}></Icon>
<style>
:global(.g_weskb6e) {
  fill: currentColor;
  d: path("M6 8.829v3.17c.867-.65 1.917-1 3-.999h6a3.01 3.01 0 0 0 2.896-2.21a3 3 0 1 1 2.032.064A5.01 5.01 0 0 1 15 13H9a3.01 3.01 0 0 0-2.896 2.21A3 3 0 1 1 4 15.171V8.829a3 3 0 1 1 2 0");
}

</style>

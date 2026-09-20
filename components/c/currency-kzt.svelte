<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="poz8jtbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-kzt" {...props}></Icon>
<style>
:global(.poz8jtbxq) {
  fill: currentColor;
  d: path("M208 96a8 8 0 0 1-8 8h-64v112a8 8 0 0 1-16 0V104H56a8 8 0 0 1 0-16h144a8 8 0 0 1 8 8M56 64h144a8 8 0 0 0 0-16H56a8 8 0 0 0 0 16");
}

</style>

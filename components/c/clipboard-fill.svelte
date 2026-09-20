<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bhi4fweyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:clipboard-fill" {...props}></Icon>
<style>
:global(.bhi4fweyc) {
  fill: currentColor;
  d: path("M200 32h-36.26a47.92 47.92 0 0 0-71.48 0H56a16 16 0 0 0-16 16v168a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-72 0a32 32 0 0 1 32 32H96a32 32 0 0 1 32-32");
}

</style>

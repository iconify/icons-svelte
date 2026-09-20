<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c_tekzb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:club-fill" {...props}></Icon>
<style>
:global(.c_tekzb4f) {
  fill: currentColor;
  d: path("M240 144a56 56 0 0 1-84.81 48h-4.44l8.91 29.7A8 8 0 0 1 152 232h-48a8 8 0 0 1-7.66-10.3l8.91-29.7h-4.44A56 56 0 1 1 72 88h2.33a56 56 0 1 1 107.34 0H184a56.06 56.06 0 0 1 56 56");
}

</style>

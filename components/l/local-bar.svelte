<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7g59fbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:local-bar" {...props}></Icon>
<style>
:global(.x7g59fbsb) {
  fill: currentColor;
  d: path("M21 5V3H3v2l8 9v5H6v2h12v-2h-5v-5zM7.43 7L5.66 5h12.69l-1.78 2z");
}

</style>

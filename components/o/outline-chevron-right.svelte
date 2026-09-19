<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qap61s_na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-chevron-right" {...props}></Icon>
<style>
:global(.qap61s_na) {
  fill: currentColor;
  d: path("M10 6L8.59 7.41L13.17 12l-4.58 4.59L10 18l6-6z");
}

</style>

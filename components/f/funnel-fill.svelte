<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c--bkl96q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:funnel-fill" {...props}></Icon>
<style>
:global(.c--bkl96q) {
  fill: currentColor;
  d: path("m227.81 66.76l-.08.09L160 139.17v55.49a16 16 0 0 1-7.13 13.34l-32 21.34A16 16 0 0 1 96 216v-76.83L28.27 66.85l-.08-.09A16 16 0 0 1 40 40h176a16 16 0 0 1 11.84 26.76Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew2xp-bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-sheets-outline-sharp" {...props}></Icon>
<style>
:global(.ew2xp-bxh) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-7.384h14V5H5zm0 1V19h14v-5.384zm0 0V19z");
}

</style>

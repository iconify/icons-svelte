<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jfgol8tly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-centered-fill" {...props}></Icon>
<style>
:global(.jfgol8tly) {
  fill: currentColor;
  d: path("M232 56v128a16 16 0 0 1-16 16h-60.43l-13.68 23.94a16 16 0 0 1-27.78 0L100.43 200H40a16 16 0 0 1-16-16V56a16 16 0 0 1 16-16h176a16 16 0 0 1 16 16");
}

</style>

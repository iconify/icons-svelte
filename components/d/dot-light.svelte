<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l_trz_fti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dot-light" {...props}></Icon>
<style>
:global(.l_trz_fti) {
  fill: currentColor;
  d: path("M138 128a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>

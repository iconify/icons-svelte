<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m8s5b_bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-line-down-left" {...props}></Icon>
<style>
:global(.m8s5b_bfu) {
  fill: currentColor;
  d: path("M232 48a8 8 0 0 1-8 8H48a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8m-53.66 42.34L80 188.69V112a8 8 0 0 0-16 0v96a8 8 0 0 0 8 8h96a8 8 0 0 0 0-16H91.31l98.35-98.34a8 8 0 0 0-11.32-11.32");
}

</style>

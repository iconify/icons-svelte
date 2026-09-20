<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gkvikvvea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:anchor-simple-fill" {...props}></Icon>
<style>
:global(.gkvikvvea) {
  fill: currentColor;
  d: path("M232 120a104 104 0 0 1-208 0a8 8 0 0 1 8-8h24a8 8 0 0 1 0 16H40.36A88.15 88.15 0 0 0 120 207.63V90.83a28 28 0 1 1 16 0v116.8A88.15 88.15 0 0 0 215.64 128H200a8 8 0 0 1 0-16h24a8 8 0 0 1 8 8");
}

</style>

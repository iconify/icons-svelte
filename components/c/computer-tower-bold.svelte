<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ik_7dybog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:computer-tower-bold" {...props}></Icon>
<style>
:global(.ik_7dybog) {
  fill: currentColor;
  d: path("M84 76a12 12 0 0 1 12-12h64a12 12 0 0 1 0 24H96a12 12 0 0 1-12-12m12 52h64a12 12 0 0 0 0-24H96a12 12 0 0 0 0 24m116-88v176a20 20 0 0 1-20 20H64a20 20 0 0 1-20-20V40a20 20 0 0 1 20-20h128a20 20 0 0 1 20 20m-24 4H68v168h120Zm-60 124a16 16 0 1 0 16 16a16 16 0 0 0-16-16");
}

</style>

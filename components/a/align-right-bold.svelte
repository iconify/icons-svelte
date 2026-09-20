<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="puwyxc_2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-right-bold" {...props}></Icon>
<style>
:global(.puwyxc_2t) {
  fill: currentColor;
  d: path("M228 40v176a12 12 0 0 1-24 0V40a12 12 0 0 1 24 0m-40 24v36a20 20 0 0 1-20 20H80a20 20 0 0 1-20-20V64a20 20 0 0 1 20-20h88a20 20 0 0 1 20 20m-24 4H84v28h80Zm24 88v36a20 20 0 0 1-20 20H40a20 20 0 0 1-20-20v-36a20 20 0 0 1 20-20h128a20 20 0 0 1 20 20m-24 4H44v28h120Z");
}

</style>

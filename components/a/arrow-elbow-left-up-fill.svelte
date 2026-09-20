<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d72na3bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-left-up-fill" {...props}></Icon>
<style>
:global(.d72na3bdt) {
  fill: currentColor;
  d: path("M240 192a8 8 0 0 1-8 8H88a8 8 0 0 1-8-8v-88H40a8 8 0 0 1-5.66-13.66l48-48a8 8 0 0 1 11.32 0l48 48A8 8 0 0 1 136 104H96v80h136a8 8 0 0 1 8 8");
}

</style>

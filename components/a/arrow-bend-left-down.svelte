<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bjezrcqct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-bend-left-down" {...props}></Icon>
<style>
:global(.bjezrcqct) {
  fill: currentColor;
  d: path("M208 32a8 8 0 0 1-8 8a88.1 88.1 0 0 0-88 88v76.69l34.34-34.35a8 8 0 0 1 11.32 11.32l-48 48a8 8 0 0 1-11.32 0l-48-48a8 8 0 0 1 11.32-11.32L96 204.69V128A104.11 104.11 0 0 1 200 24a8 8 0 0 1 8 8");
}

</style>

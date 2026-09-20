<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y2sykj1-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-bend-right-down-thin" {...props}></Icon>
<style>
:global(.y2sykj1-u) {
  fill: currentColor;
  d: path("m202.83 178.83l-48 48a4 4 0 0 1-5.66 0l-48-48a4 4 0 0 1 5.66-5.66L148 214.34V128a92.1 92.1 0 0 0-92-92a4 4 0 0 1 0-8a100.11 100.11 0 0 1 100 100v86.34l41.17-41.17a4 4 0 0 1 5.66 5.66");
}

</style>

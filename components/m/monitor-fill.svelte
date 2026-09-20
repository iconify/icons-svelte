<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v-26zkb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:monitor-fill" {...props}></Icon>
<style>
:global(.v-26zkb3d) {
  fill: currentColor;
  d: path("M232 64v112a24 24 0 0 1-24 24H48a24 24 0 0 1-24-24V64a24 24 0 0 1 24-24h160a24 24 0 0 1 24 24m-72 152H96a8 8 0 0 0 0 16h64a8 8 0 0 0 0-16");
}

</style>

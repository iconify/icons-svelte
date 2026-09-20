<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dl5-007vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:device-mobile-speaker-fill" {...props}></Icon>
<style>
:global(.dl5-007vz) {
  fill: currentColor;
  d: path("M176 16H80a24 24 0 0 0-24 24v176a24 24 0 0 0 24 24h96a24 24 0 0 0 24-24V40a24 24 0 0 0-24-24m-16 48H96a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16");
}

</style>

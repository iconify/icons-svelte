<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p05dmmbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:device-tablet-camera-fill" {...props}></Icon>
<style>
:global(.p05dmmbbt) {
  fill: currentColor;
  d: path("M192 24H64a24 24 0 0 0-24 24v160a24 24 0 0 0 24 24h128a24 24 0 0 0 24-24V48a24 24 0 0 0-24-24m-64 56a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jnabebc6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:camera-plus-fill" {...props}></Icon>
<style>
:global(.jnabebc6b) {
  fill: currentColor;
  d: path("M208 56h-27.72L169 39.12A16 16 0 0 0 155.72 32h-55.44A16 16 0 0 0 87 39.12L75.72 56H48a24 24 0 0 0-24 24v112a24 24 0 0 0 24 24h160a24 24 0 0 0 24-24V80a24 24 0 0 0-24-24m-48 88h-24v24a8 8 0 0 1-16 0v-24H96a8 8 0 0 1 0-16h24v-24a8 8 0 0 1 16 0v24h24a8 8 0 0 1 0 16");
}

</style>

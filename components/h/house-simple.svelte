<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m8hk-_blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:house-simple" {...props}></Icon>
<style>
:global(.m8hk-_blc) {
  fill: currentColor;
  d: path("m219.31 108.68l-80-80a16 16 0 0 0-22.62 0l-80 80A15.87 15.87 0 0 0 32 120v96a8 8 0 0 0 8 8h176a8 8 0 0 0 8-8v-96a15.87 15.87 0 0 0-4.69-11.32M208 208H48v-88l80-80l80 80Z");
}

</style>

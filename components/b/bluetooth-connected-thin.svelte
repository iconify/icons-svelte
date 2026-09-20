<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qpmoavbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bluetooth-connected-thin" {...props}></Icon>
<style>
:global(.qpmoavbik) {
  fill: currentColor;
  d: path("M194.4 172.8L134.67 128l59.73-44.8a4 4 0 0 0 0-6.4l-64-48A4 4 0 0 0 124 32v88L66.4 76.8a4 4 0 0 0-4.8 6.4l59.73 44.8l-59.73 44.8a4 4 0 0 0 4.8 6.4L124 136v88a4 4 0 0 0 6.4 3.2l64-48a4 4 0 0 0 0-6.4M132 40l53.33 40L132 120Zm0 176v-80l53.33 40Zm-72-80a8 8 0 1 1 8-8a8 8 0 0 1-8 8m152-8a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>

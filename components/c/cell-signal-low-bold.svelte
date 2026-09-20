<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wh2_n4zet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-low-bold" {...props}></Icon>
<style>
:global(.wh2_n4zet) {
  fill: currentColor;
  d: path("M92 152v48a12 12 0 0 1-24 0v-48a12 12 0 0 1 24 0m-52 28a12 12 0 0 0-12 12v8a12 12 0 0 0 24 0v-8a12 12 0 0 0-12-12");
}

</style>

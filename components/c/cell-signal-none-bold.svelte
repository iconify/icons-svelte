<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pojefpbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-none-bold" {...props}></Icon>
<style>
:global(.pojefpbfh) {
  fill: currentColor;
  d: path("M52 192v8a12 12 0 0 1-24 0v-8a12 12 0 0 1 24 0");
}

</style>

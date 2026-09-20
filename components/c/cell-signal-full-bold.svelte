<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w5ua_v43x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-full-bold" {...props}></Icon>
<style>
:global(.w5ua_v43x) {
  fill: currentColor;
  d: path("M172 72v128a12 12 0 0 1-24 0V72a12 12 0 0 1 24 0m28-52a12 12 0 0 0-12 12v168a12 12 0 0 0 24 0V32a12 12 0 0 0-12-12m-80 80a12 12 0 0 0-12 12v88a12 12 0 0 0 24 0v-88a12 12 0 0 0-12-12m-40 40a12 12 0 0 0-12 12v48a12 12 0 0 0 24 0v-48a12 12 0 0 0-12-12m-40 40a12 12 0 0 0-12 12v8a12 12 0 0 0 24 0v-8a12 12 0 0 0-12-12");
}

</style>

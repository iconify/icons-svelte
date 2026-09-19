<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xjv1qr60m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:homee" {...props}></Icon>
<style>
:global(.xjv1qr60m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.005 20.748c-1.826-6.973-7.328-10.02-12.617-9.736a12.03 12.03 0 0 0-10.127 6.475c-12.416 2.134-10.922 18.037 0 19.52h1.114v-5.6l7.252-5l7.253 5v5.6h7.185a8.159 8.159 0 0 0-.06-16.259M18.019 37.006v-2.417");
}

</style>

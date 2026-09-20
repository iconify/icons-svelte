<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="seqb38bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-blocked-20-regular" {...props}></Icon>
<style>
:global(.seqb38bvt) {
  fill: currentColor;
  d: path("M20 10c0-5.523-4.477-10-10-10S0 4.477 0 10s4.477 10 10 10s10-4.477 10-10m-2 0a8 8 0 0 1-12.906 6.32L16.32 5.094A7.97 7.97 0 0 1 18 10m-3.094-6.32L3.68 14.906A8 8 0 0 1 14.906 3.68");
}

</style>

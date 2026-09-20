<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hgetmobsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-u-left-up-thin" {...props}></Icon>
<style>
:global(.hgetmobsi) {
  fill: currentColor;
  d: path("M204 80v88a60 60 0 0 1-120 0V41.66L42.83 82.83a4 4 0 0 1-5.66-5.66l48-48a4 4 0 0 1 5.66 0l48 48a4 4 0 0 1-5.66 5.66L92 41.66V168a52 52 0 0 0 104 0V80a4 4 0 0 1 8 0");
}

</style>

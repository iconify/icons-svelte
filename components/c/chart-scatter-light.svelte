<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jir56vokm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chart-scatter-light" {...props}></Icon>
<style>
:global(.jir56vokm) {
  fill: currentColor;
  d: path("M230 208a6 6 0 0 1-6 6H32a6 6 0 0 1-6-6V48a6 6 0 0 1 12 0v154h186a6 6 0 0 1 6 6m-98-50a10 10 0 1 0-10-10a10 10 0 0 0 10 10m-24-56a10 10 0 1 0-10-10a10 10 0 0 0 10 10m-32 72a10 10 0 1 0-10-10a10 10 0 0 0 10 10m96-48a10 10 0 1 0-10-10a10 10 0 0 0 10 10m24-40a10 10 0 1 0-10-10a10 10 0 0 0 10 10m-8 68a10 10 0 1 0 10 10a10 10 0 0 0-10-10");
}

</style>

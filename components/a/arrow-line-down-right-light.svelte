<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cq5gmob6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-line-down-right-light" {...props}></Icon>
<style>
:global(.cq5gmob6t) {
  fill: currentColor;
  d: path("M222 40a6 6 0 0 1-6 6H40a6 6 0 0 1 0-12h176a6 6 0 0 1 6 6m-30 58a6 6 0 0 0-6 6v81.52L84.24 83.76a6 6 0 0 0-8.48 8.48L177.52 194H96a6 6 0 0 0 0 12h96a6 6 0 0 0 6-6v-96a6 6 0 0 0-6-6");
}

</style>

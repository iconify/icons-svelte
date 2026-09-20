<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c_z7s1b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-kzt-light" {...props}></Icon>
<style>
:global(.c_z7s1b_x) {
  fill: currentColor;
  d: path("M206 96a6 6 0 0 1-6 6h-66v114a6 6 0 0 1-12 0V102H56a6 6 0 0 1 0-12h144a6 6 0 0 1 6 6M56 62h144a6 6 0 0 0 0-12H56a6 6 0 0 0 0 12");
}

</style>

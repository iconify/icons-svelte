<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r8yweqb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-square-up-right-thin" {...props}></Icon>
<style>
:global(.r8yweqb_g) {
  fill: currentColor;
  d: path("M208 36H48a12 12 0 0 0-12 12v160a12 12 0 0 0 12 12h160a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12m4 172a4 4 0 0 1-4 4H48a4 4 0 0 1-4-4V48a4 4 0 0 1 4-4h160a4 4 0 0 1 4 4ZM164 96v48a4 4 0 0 1-8 0v-38.34l-57.17 57.17a4 4 0 0 1-5.66-5.66L150.34 100H112a4 4 0 0 1 0-8h48a4 4 0 0 1 4 4");
}

</style>

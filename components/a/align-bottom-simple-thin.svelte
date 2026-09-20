<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c8w3wt7vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-bottom-simple-thin" {...props}></Icon>
<style>
:global(.c8w3wt7vh) {
  fill: currentColor;
  d: path("M204 232a4 4 0 0 1-4 4H56a4 4 0 0 1 0-8h144a4 4 0 0 1 4 4M84 192V40a12 12 0 0 1 12-12h64a12 12 0 0 1 12 12v152a12 12 0 0 1-12 12H96a12 12 0 0 1-12-12m8 0a4 4 0 0 0 4 4h64a4 4 0 0 0 4-4V40a4 4 0 0 0-4-4H96a4 4 0 0 0-4 4Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-eq7acky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aircraft-paint" {...props}></Icon>
<style>
:global(.z-eq7acky) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h6v9.5H3Zm2 0V9.5h2.5m7 9h7v-15H19ZM10 7l3-2m-2.5 5l3 .75");
}

</style>

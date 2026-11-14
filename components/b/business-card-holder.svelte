<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evz-nwjsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-card-holder" {...props}></Icon>
<style>
:global(.evz-nwjsu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13.5v-9A1.5 1.5 0 0 1 7.5 3h9A1.5 1.5 0 0 1 18 4.5v9m-15.5 0h19l-2 6.5h-15ZM9 7h6m-6 3h3");
}

</style>

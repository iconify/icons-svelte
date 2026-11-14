<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd9x23sas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:anamorphic-lens" {...props}></Icon>
<style>
:global(.hd9x23sas) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h9v8H3Zm9 4a4 8.5 0 1 0 8 0a4 8.5 0 1 0-8 0Zm2.5 0h7.25");
}

</style>

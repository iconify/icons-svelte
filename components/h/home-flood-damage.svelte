<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1hczwhdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:home-flood-damage" {...props}></Icon>
<style>
:global(.d1hczwhdd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13V9.5L12 3.25l7.5 6.25V13m-17 3.5a2.75 2.75 0 0 1 5.5 0a2.75 2.75 0 0 1 5.5 0a2.75 2.75 0 0 1 5.5 0M5 21a2.75 2.75 0 0 1 5.5 0a2.75 2.75 0 0 1 5.5 0a2.75 2.75 0 0 1 5.5 0");
}

</style>

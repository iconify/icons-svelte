<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt69v0syi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-cleaning" {...props}></Icon>
<style>
:global(.pt69v0syi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m21.5 2.5l-7 7m0 0L3 14a11 11 0 0 0 7 7Zm-2 2l-6.25 4.25M13 12.5L9.5 19m6 1.5h.01m2.99 0h.01m2.99 0h.01");
}

</style>

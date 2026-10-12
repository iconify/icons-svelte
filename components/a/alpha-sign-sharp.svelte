<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltous0i7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alpha-sign-sharp" {...props}></Icon>
<style>
:global(.ltous0i7l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 5.5c-1.25 5-3.75 12.25-8 12.25c-3 0-4.75-2.5-4.75-5.75s2-5.75 5-5.75c4.25 0 6 6.5 8 10.75l.625 1.25H20");
}

</style>

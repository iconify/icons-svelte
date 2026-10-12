<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w19fhwbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:battery-sharp" {...props}></Icon>
<style>
:global(.w19fhwbsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h16v10.5h-16zm18.5 3.75v3M6 10v4m3.25-4v4m3.25-4v4m3.25-4v4");
}

</style>

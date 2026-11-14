<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra0fumbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:impeachment" {...props}></Icon>
<style>
:global(.ra0fumbop) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.52 9.591l7.071-7.071l3.889 3.889l-7.071 7.071ZM11 10l5.5 5.5m-5 3h10v3h-10Z");
}

</style>

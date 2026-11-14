<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zu1dnfbxe"/><path class="uugp5fyry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bluebird" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uugp5fyry) {
  d: path("M12 13.25C11.5 9 13 6.5 16.5 5c0 2.5-.5 4.5-1.5 6.25M16.75 14h.01");
}

:global(.zu1dnfbxe) {
  d: path("m21 13.5l-2.75-1.25c-1.5-1.5-4.75-1.25-6.25 1L4.5 12l2 3.5L5 18l5-1c2.5 2.25 6.5 1.75 8-2.25Z");
}

</style>

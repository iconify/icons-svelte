<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="konkmjbiw"/><path class="mmnk2jbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:reaction-add" {...props}></Icon>
<style>
:global(.konkmjbiw) {
  d: path("M12.476 19.371a8.5 8.5 0 1 1 6.895-6.895M8.25 9h.01m5.49 0h.01");
}

:global(.mmnk2jbdl) {
  d: path("M7.5 13c1.25 2.25 4.5 2.5 6.25.75M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

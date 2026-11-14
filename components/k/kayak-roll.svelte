<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvr309zej"/><path class="p9tq0zrti"/><path class="u-ec9j55s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kayak-roll" {...props}></Icon>
<style>
:global(.fvr309zej) {
  d: path("M5.75 12c2.75 3 9.75 3 12.5 0c-2.75-2-9.75-2-12.5 0Z");
}

:global(.p9tq0zrti) {
  d: path("M7.5 19.75a9 9 0 1 1 9 0");
}

:global(.u-ec9j55s) {
  d: path("m17.25 16.75l-.75 3l3 .75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

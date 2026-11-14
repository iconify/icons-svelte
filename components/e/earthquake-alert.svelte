<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e17uprz5n"/><path class="wg2llmbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:earthquake-alert" {...props}></Icon>
<style>
:global(.e17uprz5n) {
  d: path("M15.2 20.5H4v-18h13v9.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wg2llmbhq) {
  d: path("m4 9l3.5 3.5l3-3.5l3 3.5l3.5-3m1 5V18m0 3h.01");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="db_wykbsk"/><path class="jywqgfdki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:elevator-building" {...props}></Icon>
<style>
:global(.db_wykbsk) {
  d: path("M3.5 8h17v13.5h-17Z");
}

:global(.jywqgfdki) {
  d: path("M6.5 11h11v10.5h-11Zm5.5 0v10.5M8.5 6V2.5M6.75 4.25L8.5 2.5l1.75 1.75M15.5 2.5V6m-1.75-1.75L15.5 6l1.75-1.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

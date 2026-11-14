<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c2a3fh_2u"/><path class="jnl5_bc4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:constant-pi" {...props}></Icon>
<style>
:global(.c2a3fh_2u) {
  d: path("M3.5 7q1-2.5 3.5-2.5h13.5m-11 0L7.5 20");
}

:global(.jnl5_bc4s) {
  d: path("M15.5 4.5V17a3 3 0 0 0 3 3h1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

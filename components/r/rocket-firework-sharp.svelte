<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8zz1ybap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rocket-firework-sharp" {...props}></Icon>
<style>
:global(.c8zz1ybap) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.32 3.26l2.36 3.73l.32.51H9l.32-.51l2.36-3.73l.32-.51zM9 7.5h6v7.25H9zm0 3h6m-3 4.25v6.5m-3-4l-1.75 2.5m7.75-2.5l1.75 2.5");
}

</style>

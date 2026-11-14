<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmqotzb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cell-edit" {...props}></Icon>
<style>
:global(.fmqotzb2a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19v19h-19Zm0 9.5h19M12 12v9.5M6 7.25h4m3.5-2.5v5m-1.25-5h2.5m-2.5 5h2.5");
}

</style>

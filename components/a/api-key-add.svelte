<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f-qvggbdk"/><path class="g9-9z2bcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:api-key-add" {...props}></Icon>
<style>
:global(.f-qvggbdk) {
  d: path("M12.2 19H2.5V2.5H19v9.7");
}

:global(.g9-9z2bcm) {
  d: path("M5.5 8.25h5v5h-5Zm5 2.5H16v1.4M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

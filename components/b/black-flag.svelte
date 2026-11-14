<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l4a0e8cji"/><path class="hh633abth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:black-flag" {...props}></Icon>
<style>
:global(.hh633abth) {
  d: path("M12 13.5v5m-3.5 3l3.5-3l3.5 3");
}

:global(.l4a0e8cji) {
  fill: currentColor;
  d: path("M7.5 2.5h9v11h-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

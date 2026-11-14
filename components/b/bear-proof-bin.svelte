<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cxsvbebba"/><path class="ilse9llnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bear-proof-bin" {...props}></Icon>
<style>
:global(.cxsvbebba) {
  d: path("M10 6V3.5h4V6M4 6h16M5.5 6l1.25 13.5a1.5 1.5 0 0 0 1.5 1.5h7.5a1.5 1.5 0 0 0 1.5-1.5L18.5 6");
}

:global(.ilse9llnc) {
  d: path("M9 12.5h6V17H9Zm1.5 0V11a1.5 1.5 0 0 1 3 0v1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

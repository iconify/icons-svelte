<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aghm759nx"/><path class="iz30smblu"/><path class="enwzisbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electromagnetic-spectrum" {...props}></Icon>
<style>
:global(.aghm759nx) {
  d: path("M3 5q4.5-4 9 0t9 0");
}

:global(.enwzisbwr) {
  d: path("M3 19q1.5-4 3 0t3 0t3 0t3 0t3 0t3 0");
}

:global(.iz30smblu) {
  d: path("M3 12q2.25-4 4.5 0t4.5 0t4.5 0t4.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

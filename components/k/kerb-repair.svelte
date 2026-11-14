<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lwztzqa1i"/><path class="gc556ubmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kerb-repair" {...props}></Icon>
<style>
:global(.gc556ubmm) {
  d: path("M7.5 4.5V16h5v-5.5m8.75 5.25A2.25 2.25 0 1 1 19 13.5m-1.5 3.75l-3 3");
}

:global(.lwztzqa1i) {
  d: path("M2.5 4.5h8a2 2 0 0 1 2 2v4h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bg5_o71pf"/><path class="hbv8nob4p"/><path class="trn1rwa5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:remote-patient-monitoring" {...props}></Icon>
<style>
:global(.bg5_o71pf) {
  d: path("M14.5 14H4V3.5h15v8.1M2.5 17h8.7");
}

:global(.hbv8nob4p) {
  d: path("M6.5 9h2l1.25-2.5l1.5 5L12.5 9h4m-2.25 9L18 14.5l3.75 3.5");
}

:global(.trn1rwa5g) {
  d: path("M15.5 17v4.5h5V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

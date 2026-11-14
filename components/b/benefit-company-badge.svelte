<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nmvzogu3o"/><path class="a42iin_iw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:benefit-company-badge" {...props}></Icon>
<style>
:global(.a42iin_iw) {
  d: path("m8.25 12.25l2.5 2.5l5-5");
}

:global(.nmvzogu3o) {
  d: path("m21.5 12l-3.25 3.75l-1.5 4.5l-4.75-1l-4.75 1l-1.5-4.5L2.5 12l3.25-3.75l1.5-4.5l4.75 1l4.75-1l1.5 4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

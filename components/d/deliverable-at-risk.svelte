<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pbwfr0bwn"/><path class="accbv0bzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deliverable-at-risk" {...props}></Icon>
<style>
:global(.accbv0bzp) {
  d: path("m2.5 6.75l8 4.25l8-4.25m-8 4.25v9.5m7.5-5.75v3.5M18 21h.01");
}

:global(.pbwfr0bwn) {
  d: path("M15.196 18.005L10.5 20.5l-8-4.25v-9.5l8-4.25l8 4.25v5.241");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

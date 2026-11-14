<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qd449rbnv"/><path class="yckmedchu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bio-lab" {...props}></Icon>
<style>
:global(.qd449rbnv) {
  d: path("m4.018 4.103l3.464-2l4.5 7.794l-3.464 2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yckmedchu) {
  d: path("M9 20.5c4-1.5 5.5-7.5 2.5-11m-8 5H10m-6.5 6H13m4-6.5v5.5a1.75 1.75 0 0 0 3.5 0V14M16 14h5.5");
}

</style>

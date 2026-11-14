<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fzryzxb-d"/><path class="pf5k29b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:exit-ramp-left" {...props}></Icon>
<style>
:global(.fzryzxb-d) {
  d: path("M17.5 2.5v19m0-4c0-4-2.5-5.5-5-8L6 3");
}

:global(.pf5k29b9w) {
  d: path("M6 8.5V3h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

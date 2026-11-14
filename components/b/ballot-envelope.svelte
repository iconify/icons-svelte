<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky431dr5k"/><path class="ujfsvl36y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ballot-envelope" {...props}></Icon>
<style>
:global(.ky431dr5k) {
  d: path("M2.5 11h19v10.5h-19ZM6 11V2.5h12V11");
}

:global(.ujfsvl36y) {
  d: path("M2.75 12L12 17l9.25-5M9.75 6.25L11.5 8l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

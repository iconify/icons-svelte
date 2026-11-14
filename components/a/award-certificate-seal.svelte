<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tw6vs5-jp"/><path class="erlecubjt"/><path class="fi-x7fb9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:award-certificate-seal" {...props}></Icon>
<style>
:global(.erlecubjt) {
  d: path("M13 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.fi-x7fb9s) {
  d: path("M14 17.25v4L16 20l2 1.25v-4");
}

:global(.tw6vs5-jp) {
  d: path("M10.3 16.5H2.5v-13h19v10.2M6 7.5h12m-12 4h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

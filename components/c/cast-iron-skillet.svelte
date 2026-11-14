<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hmfspybaw"/><path class="qs513ccfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cast-iron-skillet" {...props}></Icon>
<style>
:global(.hmfspybaw) {
  d: path("M2.5 11.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm14 0h5");
}

:global(.qs513ccfb) {
  d: path("M6 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

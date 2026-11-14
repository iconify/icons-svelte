<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em_x23u7l"/><path class="imc_7wbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:protostar" {...props}></Icon>
<style>
:global(.em_x23u7l) {
  d: path("m12 3.5l1.5 7l3 1.5l-3 1.5l-1.5 7l-1.5-7l-3-1.5l3-1.5Z");
}

:global(.imc_7wbfu) {
  d: path("M2.5 12a9.5 3.25 0 1 0 19 0a9.5 3.25 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2ciopbql"/><path class="zbnoncc8l"/><path class="si7xw1b6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:brainwave-eeg" {...props}></Icon>
<style>
:global(.p2ciopbql) {
  d: path("M2.5 7H5l1.5-3l2 6L10 7h11.5");
}

:global(.si7xw1b6h) {
  d: path("M2.5 17H12l1.5-2.5l2 5L17 17h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zbnoncc8l) {
  d: path("M2.5 12H8l1.5-3l2 6l1.5-3h8.5");
}

</style>

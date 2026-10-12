<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a81qvikhv"/><path class="q_nfnc6mi"/><path class="ekpyzob7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alert-banner-sharp" {...props}></Icon>
<style>
:global(.a81qvikhv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5h18.5v11H2.75zM7 9.5v3");
}

:global(.ekpyzob7n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 12h7.25");
}

:global(.q_nfnc6mi) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 15h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

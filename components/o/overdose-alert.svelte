<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kczr05bxa"/><path class="yml1_obiq"/><path class="aziuo-zel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:overdose-alert" {...props}></Icon>
<style>
:global(.aziuo-zel) {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM18 16v2m0 2h.01");
}

:global(.kczr05bxa) {
  d: path("M2.5 6.5h9V14h-9Zm10 8h-1V6H15v6.2M4.5 10.25h5M13.25 6v7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yml1_obiq) {
  fill: currentColor;
  d: path("M17 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-.558 3.611l.592-1.269l3.172 1.48");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpkep8bsv"/><path class="t-t6zsj_c"/><path class="ecjiacbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mention" {...props}></Icon>
<style>
:global(.ecjiacbfy) {
  d: path("M13.5 10v2.75a1.25 1.25 0 0 0 2.5 0V12a4.25 4.25 0 1 0-2 3.75");
}

:global(.hpkep8bsv) {
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5Z");
}

:global(.t-t6zsj_c) {
  d: path("M9.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

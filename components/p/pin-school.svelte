<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1fv66b2f"/><path class="ntz2xubmj"/><path class="ucm4t8bjc"/><path class="ys6zy8cep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-school" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1fv66b2f) {
  d: path("M12 22c-3.5-2.5-9-6.5-9-11a9 9 0 0 1 18 0c0 4.5-5.5 8.5-9 11");
}

:global(.ntz2xubmj) {
  d: path("M8 14.75v-2.419a1.5 1.5 0 0 1 .705-1.272l2.5-1.562a1.5 1.5 0 0 1 1.59 0l2.5 1.562A1.5 1.5 0 0 1 16 12.331v2.419a1.5 1.5 0 0 1-1.5 1.5h-5a1.5 1.5 0 0 1-1.5-1.5M12 9V5");
}

:global(.ucm4t8bjc) {
  fill: currentColor;
  d: path("m13.154 5.481l.346.144a.677.677 0 0 1 0 1.25l-.346.144A.833.833 0 0 1 12 6.25a.833.833 0 0 1 1.154-.769");
}

:global(.ys6zy8cep) {
  d: path("M12 13za1.25 1.25 0 0 1 1.25 1.25V15A1.25 1.25 0 0 1 12 16.25A1.25 1.25 0 0 1 10.75 15v-.75A1.25 1.25 0 0 1 12 13");
}

</style>

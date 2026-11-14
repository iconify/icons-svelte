<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r53h7er2b"/><path class="n_95hacow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:air-brush-3d" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_95hacow) {
  d: path("M15 16.25L18 18l3-1.75M18 18v3.5");
}

:global(.r53h7er2b) {
  d: path("M20.5 3.5L13 11m-.795 5.832C10.263 18.879 7.278 20.185 3.5 20.5c.5-6 3.5-10 8-11l3 3a10 10 0 0 1-.261.944m4.517 1.497l1.5.875A1.5 1.5 0 0 1 21 17.112v1.776a1.5 1.5 0 0 1-.744 1.296l-1.5.875a1.5 1.5 0 0 1-1.512 0l-1.5-.875A1.5 1.5 0 0 1 15 18.888v-1.776a1.5 1.5 0 0 1 .744-1.296l1.5-.875a1.5 1.5 0 0 1 1.512 0");
}

</style>

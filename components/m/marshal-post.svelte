<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmct_qb4e"/><path class="qumzlubap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marshal-post" {...props}></Icon>
<style>
:global(.fmct_qb4e) {
  d: path("m4.043 10.483l3.5-3.334a1.75 1.75 0 0 1 2.414 0l3.5 3.334A1.75 1.75 0 0 1 14 11.75v7a1.75 1.75 0 0 1-1.75 1.75h-7a1.75 1.75 0 0 1-1.75-1.75v-7a1.75 1.75 0 0 1 .543-1.267M17.5 20.5v-17m0 0h4l-1.25 2.25L21.5 8h-4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qumzlubap) {
  d: path("M7 20.5V16h3.5v4.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7fh31b2x"/><path class="imh7vgi-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:church-spire" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.imh7vgi-c) {
  d: path("M10.5 21v-4.5h3V21");
}

:global(.n7fh31b2x) {
  d: path("M6 21v-9h12v9M8 12l4-7.5l4 7.5m-4-7.5v-2");
}

</style>

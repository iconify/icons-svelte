<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aj1uncbqw"/><path class="y4-ssjnrw"/><path class="om9c7ck0x"/><path class="osdsz4bam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:degree-fahrenheit-outline-thin" {...props}></Icon>
<style>
:global(.aj1uncbqw) {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.om9c7ck0x) {
  d: path("M13 8h7");
}

:global(.osdsz4bam) {
  d: path("M13 14h5");
}

:global(.y4-ssjnrw) {
  d: path("M13 8v12");
}

</style>

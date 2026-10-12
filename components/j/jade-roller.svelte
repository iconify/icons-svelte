<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q1cg06-mt"/><path class="b303drbzs"/><rect class="f9auxb1ek"/><rect class="rz6a1acmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jade-roller" {...props}></Icon>
<style>
:global(.b303drbzs) {
  d: path("M3.25 5v4.5h17.5V5M12 9.5v2.25");
}

:global(.f9auxb1ek) {
  width: 3px;
  height: 4px;
  x: 10.5px;
  y: 11.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q1cg06-mt) {
  width: 11.5px;
  height: 4.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 2.25px;
}

:global(.rz6a1acmx) {
  width: 6px;
  height: 3px;
  x: 9px;
  y: 18.25px;
  rx: 1.5px;
}

</style>

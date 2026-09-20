<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vms-s--ti"/><path class="kchk9kbsh"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delta-table-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kchk9kbsh) {
  d: path("M4 13.5h16");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.vms-s--ti) {
  d: path("m12 4 4.5 4.5h-9Z");
}

</style>

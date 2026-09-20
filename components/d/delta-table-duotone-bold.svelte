<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jrph-kbuv"/><path class="vms-s--ti"/><path class="kchk9kbsh"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delta-table-duotone-bold" {...props}></Icon>
<style>
:global(.jrph-kbuv) {
  fill: currentColor;
  d: path("m12 4 4.5 4.5h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kchk9kbsh) {
  d: path("M4 13.5h16");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vms-s--ti) {
  d: path("m12 4 4.5 4.5h-9Z");
}

</style>

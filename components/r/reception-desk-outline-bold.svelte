<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zugrvnb7t"/><path class="a0e2epbbx"/><path class="ltriwmbuu"/><path class="us2evabuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reception-desk-outline-bold" {...props}></Icon>
<style>
:global(.a0e2epbbx) {
  d: path("M4 13v7h16v-7");
}

:global(.ltriwmbuu) {
  d: path("M8 10a4 4 0 0 1 8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.us2evabuy) {
  d: path("M12 5.5V8");
}

:global(.zugrvnb7t) {
  d: path("M2 13h20");
}

</style>

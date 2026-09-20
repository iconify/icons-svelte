<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t5xz5pb7f"/><path class="hpmnlabtt"/><path class="qyha_vbqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kite-outline-bold" {...props}></Icon>
<style>
:global(.hpmnlabtt) {
  d: path("M6 9h12");
}

:global(.qyha_vbqa) {
  d: path("M12 15c2 2 -2 3 0 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t5xz5pb7f) {
  d: path("m12 3 6 6 -6 6 -6 -6Z");
}

</style>

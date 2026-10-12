<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="j34tj1bnj"/><circle class="p374bcbxq"/><circle class="id0kkljei"/><circle class="u9x99hfmy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-share" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.id0kkljei) {
  cx: 19.5px;
  cy: 14.75px;
  r: 1.25px;
}

:global(.it-qfxbvy) {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

:global(.j34tj1bnj) {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4m4.25 4.5l2-1.25m-2 2.75l2 1.25");
}

:global(.p374bcbxq) {
  cx: 15.25px;
  cy: 17.5px;
  r: 1.5px;
}

:global(.u9x99hfmy) {
  cx: 19.5px;
  cy: 20px;
  r: 1.25px;
}

</style>

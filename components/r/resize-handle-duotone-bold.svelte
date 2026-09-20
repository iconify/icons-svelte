<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tr01qf3od"/><path class="q7tcssvtu"/><path class="jcnar9-zu"/><path class="htx64eiti"/><path class="j0xsopbwy"/><path class="dq5olwsrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:resize-handle-duotone-bold" {...props}></Icon>
<style>
:global(.dq5olwsrs) {
  d: path("m21.5 18.5 -3 3");
}

:global(.htx64eiti) {
  d: path("m21.5 5.5 -16 16");
}

:global(.j0xsopbwy) {
  d: path("m21.5 12.5 -9 9");
}

:global(.jcnar9-zu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21.5 18.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q7tcssvtu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21.5 12.5 -9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tr01qf3od) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21.5 5.5 -16 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

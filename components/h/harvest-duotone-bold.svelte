<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hzasgob7a"/><path class="ncqq4rbxm"/><path class="yobyeezoh"/><path class="hpm6v1-ys"/><path class="sfnyx4wnk"/><path class="h-el3xdlg"/><path class="zjyeu0bzf"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:harvest-duotone-bold" {...props}></Icon>
<style>
:global(.h-el3xdlg) {
  d: path("M12 6v14");
}

:global(.hpm6v1-ys) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hzasgob7a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.ncqq4rbxm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfnyx4wnk) {
  d: path("M6 6v14");
}

:global(.yobyeezoh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zjyeu0bzf) {
  d: path("M18 6v14");
}

</style>

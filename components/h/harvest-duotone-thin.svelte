<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyvlwlbog"/><path class="ai1ljvb5z"/><path class="v5lk2tbod"/><path class="hsnj9o-9y"/><path class="sfnyx4wnk"/><path class="h-el3xdlg"/><path class="zjyeu0bzf"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:harvest-duotone-thin" {...props}></Icon>
<style>
:global(.ai1ljvb5z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-el3xdlg) {
  d: path("M12 6v14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hyvlwlbog) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.sfnyx4wnk) {
  d: path("M6 6v14");
}

:global(.v5lk2tbod) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zjyeu0bzf) {
  d: path("M18 6v14");
}

</style>

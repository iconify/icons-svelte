<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkxdfrn3s"/><path class="vniunubej"/><path class="biz7t_4gn"/><path class="aryvw86tm"/><path class="ozi-k-boi"/><path class="wlp3ibbib"/><path class="c3wl0l-ou"/><path class="yhbiuccel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-drop-duotone-thin" {...props}></Icon>
<style>
:global(.aryvw86tm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 16 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.biz7t_4gn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.dkxdfrn3s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.vniunubej) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

:global(.yhbiuccel) {
  d: path("m16 16 3 3 3 -3");
}

</style>

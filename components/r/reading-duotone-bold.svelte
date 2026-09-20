<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fnnwjc5dd"/><path class="n0na4yb0n"/><path class="o2o7qi0tg"/><path class="jq5siqonn"/><path class="t-0jg7bvk"/><path class="x4kxwubfs"/><path class="m0msdy1bm"/><path class="exo870qhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-duotone-bold" {...props}></Icon>
<style>
:global(.exo870qhz) {
  d: path("M15 11h4");
}

:global(.fnnwjc5dd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jq5siqonn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m0msdy1bm) {
  d: path("M5 11h4");
}

:global(.n0na4yb0n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o2o7qi0tg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t-0jg7bvk) {
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
}

:global(.x4kxwubfs) {
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
}

</style>

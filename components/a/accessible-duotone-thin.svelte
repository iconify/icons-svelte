<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="buov3xbst"/><path class="fmh7aab_f"/><path class="yz2g0nbyn"/><path class="feojlrbcu"/><path class="a7n0rwu5e"/><path class="rf4kl9b8f"/><path class="ritvf8n1n"/><path class="hynwb207w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accessible-duotone-thin" {...props}></Icon>
<style>
:global(.a7n0rwu5e) {
  d: path("M2 18v-5h5V8h5");
}

:global(.buov3xbst) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-5h5V8h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.feojlrbcu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fmh7aab_f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hynwb207w) {
  d: path("M19 15v3");
}

:global(.rf4kl9b8f) {
  d: path("m12 8 7 7");
}

:global(.ritvf8n1n) {
  d: path("M2 18h17");
}

:global(.yz2g0nbyn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fo2fjz_qj"/><path class="s2ztwmbwx"/><path class="ttx6bbv4v"/><path class="xrnoeq00r"/><path class="bj2hlhbfp"/><path class="ic_pehd5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollout-duotone-thin" {...props}></Icon>
<style>
:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.fo2fjz_qj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.s2ztwmbwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ttx6bbv4v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xrnoeq00r) {
  d: path("M3 7h6");
}

</style>

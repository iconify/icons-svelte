<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qv4kmp1lx"/><path class="v1898kstq"/><path class="fajysd5vp"/><path class="qvqi41cih"/><path class="j2aic6ujd"/><path class="c3xkdj8uw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-escalate-duotone-thin" {...props}></Icon>
<style>
:global(.c3xkdj8uw) {
  d: path("M14.5 5H19v4.5");
}

:global(.fajysd5vp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 5H19v4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2aic6ujd) {
  d: path("m12 12 7 -7");
}

:global(.qv4kmp1lx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qvqi41cih) {
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
}

:global(.v1898kstq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

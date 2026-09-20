<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7f50bciz"/><path class="ngex86bxe"/><path class="wrdzdhojp"/><path class="tr_jskylo"/><path class="ftrg70bds"/><path class="yih0nfb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:min-p-duotone-thin" {...props}></Icon>
<style>
:global(.ftrg70bds) {
  d: path("M17 11v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ngex86bxe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.wrdzdhojp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y7f50bciz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>

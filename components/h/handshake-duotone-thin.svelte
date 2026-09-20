<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="vkx7hwi-p"/><path class="l88q_jbsc"/><path class="wplctobme"/><path class="udm6f4omu"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="f8gsx7b5s"/><path class="qs69rnufu"/><path class="xqfhg19ie"/><path class="q9rcsymqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:handshake-duotone-thin" {...props}></Icon>
<style>
:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l88q_jbsc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 8 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q9rcsymqn) {
  d: path("m6 16 3 3");
}

:global(.qs69rnufu) {
  d: path("m18 8 -3 -3");
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.udm6f4omu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 16 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vkx7hwi-p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wplctobme) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xqfhg19ie) {
  d: path("M18 16H6");
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

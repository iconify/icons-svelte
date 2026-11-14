<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j73h5bt6s"/><path class="ozdjujb5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:radio-jingle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j73h5bt6s) {
  d: path("M4.5 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m9.5-2a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.ozdjujb5g) {
  d: path("M9.5 17.5v-12l9.5-2v12M9.5 9L19 7");
}

</style>

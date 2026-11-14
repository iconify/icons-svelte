<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lylnt0bcq"/><path class="afoxwro0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:conversion-path" {...props}></Icon>
<style>
:global(.afoxwro0d) {
  d: path("m19 4.25l2 2l-2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lylnt0bcq) {
  d: path("M2.5 19.75H7v-4.5h4.5v-4.5H16v-4.5h5");
}

</style>

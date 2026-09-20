<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrvo9u_3y"/><path class="tla8vyn6c"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parcel-left-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.tla8vyn6c) {
  d: path("M12 7v8");
}

:global(.zrvo9u_3y) {
  d: path("M6 7v8h12V7Z");
}

</style>

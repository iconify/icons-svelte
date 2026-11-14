<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="agbwxyu4b"/><path class="og913g3xv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:earth-layers" {...props}></Icon>
<style>
:global(.agbwxyu4b) {
  d: path("M12 12V2.5a9.5 9.5 0 1 0 9.5 9.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.og913g3xv) {
  d: path("M12 8.5a3.5 3.5 0 0 1 3.5 3.5M12 5.5a6.5 6.5 0 0 1 6.5 6.5M12 2.5a4.5 9.5 0 0 0 0 19");
}

</style>

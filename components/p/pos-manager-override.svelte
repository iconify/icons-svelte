<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rd15cm97m"/><path class="tq2-olb6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pos-manager-override" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rd15cm97m) {
  d: path("M11.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.tq2-olb6q) {
  d: path("M9.25 6.5za3.25 3.25 0 0 1 3.25 3.25A3.25 3.25 0 0 1 9.25 13A3.25 3.25 0 0 1 6 9.75A3.25 3.25 0 0 1 9.25 6.5M8 13v6.5l1.25 1.25l1.25-1.25v-1.25h1.214M12 16.836V16.5h-1.5V13M9.25 9.75h.01M14.5 18l2.5 2.5l4.5-5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ttsqbcboh"/><path class="of-ai0ajc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:carbon-tax-tag" {...props}></Icon>
<style>
:global(.of-ai0ajc) {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.25 4.75l-5.5 5.75m-.5-5.25h.01m6.49 5h.01");
}

:global(.ttsqbcboh) {
  d: path("M12 2.5L19.5 8v11.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

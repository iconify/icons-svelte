<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="p3yzhb3te"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ear-protection-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.p3yzhb3te) {
  d: path("M8 11.5a4 4 0 0 1 8 0m-6.75 0H7V16h2.25Zm5.5 0H17V16h-2.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

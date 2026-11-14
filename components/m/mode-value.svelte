<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r13th-b-g"/><path class="odvqn7bdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mode-value" {...props}></Icon>
<style>
:global(.odvqn7bdq) {
  d: path("M3 19.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm5 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm10.5 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0-4a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.r13th-b-g) {
  fill: currentColor;
  d: path("M12.75 19.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm0-4a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

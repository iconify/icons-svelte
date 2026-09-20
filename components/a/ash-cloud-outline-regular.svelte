<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7jotynzh"/><path class="mwsvi3abz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ash-cloud-outline-regular" {...props}></Icon>
<style>
:global(.mwsvi3abz) {
  d: path("m5 21 7 -7 7 7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u7jotynzh) {
  d: path("M4 12a3.5 3.5 0 0 1 2 -6.5 4.5 4.5 0 0 1 8.5 -1A5 5 0 0 1 18 12Z");
}

</style>

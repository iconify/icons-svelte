<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mx73lcb8b"/><path class="jp0baob-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-search-duocolor-sharp" {...props}></Icon>
<style>
:global(.jp0baob-m) {
  d: path("M4 5h16v16H4Zm4-2v2m8-2v2M4 9h16");
}

:global(.mx73lcb8b) {
  stroke-opacity: 0.4;
  d: path("M9 14a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

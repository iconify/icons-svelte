<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u6thig5fy"/><path class="g4njagb-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-lock-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.g4njagb-z) {
  d: path("M9 21H4V5h16v4M8 3v2m8-2v2M4 9h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u6thig5fy) {
  stroke-opacity: 0.4;
  d: path("M13 16h8v5h-8Zm2 0v-1a2 2 0 1 1 4 0v1");
}

</style>

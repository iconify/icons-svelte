<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z19ynguch"/><path class="nd2j8pb7p"/><path class="n3wsbk_ds"/><path class="sg37fu_dx"/><path class="m724zy5bc"/><path class="qg3b3u-3z"/><path class="n7pu66d5h"/><path class="kr6epu66n"/><path class="uobswubeq"/><path class="p-u3ngpfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:family-room-duotone-bold" {...props}></Icon>
<style>
:global(.kr6epu66n) {
  d: path("M4 10V7h4v3");
}

:global(.m724zy5bc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 15.5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n3wsbk_ds) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 10V7h4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n7pu66d5h) {
  d: path("M2 13.5h10");
}

:global(.nd2j8pb7p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 13.5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p-u3ngpfy) {
  d: path("M15 15.5h7");
}

:global(.qg3b3u-3z) {
  d: path("M2 18v-8h10v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sg37fu_dx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 18v-5h7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uobswubeq) {
  d: path("M15 18v-5h7v5");
}

:global(.z19ynguch) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18v-8h10v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

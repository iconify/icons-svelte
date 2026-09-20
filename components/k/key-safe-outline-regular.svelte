<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="chrzje8tu"/><path class="u84sg0ngq"/><path class="dy-bj6bwq"/><path class="h857n5bhq"/><path class="y6kfzfgng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:key-safe-outline-regular" {...props}></Icon>
<style>
:global(.chrzje8tu) {
  d: path("M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.dy-bj6bwq) {
  d: path("M14 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.h857n5bhq) {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y6kfzfgng) {
  d: path("M14 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xi2w5nt2z"/><path class="rycj10btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-horizontal-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rycj10btr) {
  d: path("M6 13V21M12 13V21M18 13V21");
}

:global(.xi2w5nt2z) {
  stroke-opacity: 0.4;
  d: path("M3 6H10M7 3L10 6L7 9M21 6H14M17 3L14 6L17 9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_61jzbqt"/><path class="zto18nxmz"/><path class="st-dlsdww"/><path class="i4kf51esh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rhythm-outline-regular" {...props}></Icon>
<style>
:global(.i_61jzbqt) {
  d: path("M4 8v8");
}

:global(.i4kf51esh) {
  d: path("M19 5v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.st-dlsdww) {
  d: path("M14 8v8");
}

:global(.zto18nxmz) {
  d: path("M9 5v14");
}

</style>

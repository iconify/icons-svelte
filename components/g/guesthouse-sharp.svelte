<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l2x7t_bvh"/><path clip-rule="evenodd" class="lo2a_abmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:guesthouse-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l2x7t_bvh) {
  d: path("M3.998 2V4.8M3.998 4.8V17H19.998V3.2M22.928 3L19.998 3.2L3.998 4.8M3.998 4.8L1.098 5.09M9.998 17V14C9.998 12.9 10.894 12 11.998 12C13.103 12 13.998 12.9 13.998 14V17M8.998 21H14.998");
}

:global(.lo2a_abmw) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 9C9 9.55 8.552 10 8 10C7.448 10 7 9.55 7 9C7 8.45 7.448 8 8 8C8.552 8 9 8.45 9 9Z");
  stroke: none;
}

</style>

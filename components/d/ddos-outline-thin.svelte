<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghf2zyulc"/><path class="lpi5lkbmw"/><path class="wr9epib_z"/><path class="ka1ksx6kt"/><path class="u649he-6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ddos-outline-thin" {...props}></Icon>
<style>
:global(.ghf2zyulc) {
  d: path("M2 5h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka1ksx6kt) {
  d: path("M2 19h12");
}

:global(.lpi5lkbmw) {
  d: path("M2 9h12");
}

:global(.u649he-6w) {
  d: path("M18 3v18");
}

:global(.wr9epib_z) {
  d: path("M2 15h12");
}

</style>

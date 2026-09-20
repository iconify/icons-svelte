<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ucggdwbez"/><path class="bs0a9_brj"/><path class="ks8dyvldl"/><path class="yw0xzbbmi"/><path class="zd9q8ha4t"/><path class="w1_ilb-be"/><path class="pu4b1osbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ping-host-duotone-regular" {...props}></Icon>
<style>
:global(.bs0a9_brj) {
  fill: currentColor;
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ks8dyvldl) {
  d: path("M15.5 8a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pu4b1osbn) {
  d: path("M12 12h3.5");
}

:global(.ucggdwbez) {
  fill: currentColor;
  d: path("M15.5 8a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.w1_ilb-be) {
  d: path("M8.5 5.94a7 7 0 0 1 0 12.12");
}

:global(.yw0xzbbmi) {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zd9q8ha4t) {
  d: path("M7 8.54a4 4 0 0 1 0 6.92");
}

</style>

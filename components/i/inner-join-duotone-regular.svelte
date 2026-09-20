<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yg16h_b6r"/><path class="cd9o0g-4r"/><path class="ygpel9b0x"/><path class="ewesysbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:inner-join-duotone-regular" {...props}></Icon>
<style>
:global(.cd9o0g-4r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ewesysbte) {
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yg16h_b6r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ygpel9b0x) {
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
}

</style>

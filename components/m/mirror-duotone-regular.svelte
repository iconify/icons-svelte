<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a3qgyebim"/><path class="zawn-gbuw"/><path class="m7p35uguv"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mirror-duotone-regular" {...props}></Icon>
<style>
:global(.a3qgyebim) {
  fill: currentColor;
  d: path("M6 10a6 7 0 1 1 12 0 6 7 0 1 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m7p35uguv) {
  d: path("M12 17v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.zawn-gbuw) {
  d: path("M6 10a6 7 0 1 1 12 0 6 7 0 1 1 -12 0");
}

</style>

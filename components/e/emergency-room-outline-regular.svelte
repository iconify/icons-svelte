<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cfwhgr43a"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:emergency-room-outline-regular" {...props}></Icon>
<style>
:global(.cfwhgr43a) {
  d: path("M4 20v-8a8 8 0 0 1 16 0v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cib2dlbwm"/><path class="zrdou8b0n"/><path class="buon2iihn"/><path class="q8xy9tkjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:house-key-outline-regular" {...props}></Icon>
<style>
:global(.buon2iihn) {
  d: path("M16 12v4");
}

:global(.cib2dlbwm) {
  d: path("M4 15v-5l4 -4 4 4v5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q8xy9tkjr) {
  d: path("M20 12v4");
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>

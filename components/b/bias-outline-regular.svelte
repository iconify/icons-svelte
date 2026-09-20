<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bias-outline-regular" {...props}></Icon>
<style>
:global(.d23kmtbkz) {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

:global(.efyfmvbkh) {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>

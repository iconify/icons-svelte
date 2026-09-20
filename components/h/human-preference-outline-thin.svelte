<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="evty0vb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-preference-outline-thin" {...props}></Icon>
<style>
:global(.d23kmtbkz) {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

:global(.efyfmvbkh) {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

:global(.evty0vb8w) {
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>

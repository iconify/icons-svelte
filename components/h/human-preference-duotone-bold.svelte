<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o6hvby18z"/><path class="uda6dfbwy"/><path class="kr89xrare"/><path class="dl8beccds"/><path class="ujz4z0bsw"/><path class="b0695_86h"/><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="evty0vb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-preference-duotone-bold" {...props}></Icon>
<style>
:global(.b0695_86h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d23kmtbkz) {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

:global(.dl8beccds) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.efyfmvbkh) {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

:global(.evty0vb8w) {
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.kr89xrare) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o6hvby18z) {
  fill: currentColor;
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uda6dfbwy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ujz4z0bsw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>

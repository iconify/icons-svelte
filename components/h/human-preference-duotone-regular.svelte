<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o6hvby18z"/><path class="lbllh8b8w"/><path class="bxmj3jlza"/><path class="gz0-0ft4b"/><path class="kj672_yfn"/><path class="c5wjx8n3c"/><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="evty0vb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-preference-duotone-regular" {...props}></Icon>
<style>
:global(.bxmj3jlza) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c5wjx8n3c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d23kmtbkz) {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

:global(.efyfmvbkh) {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

:global(.evty0vb8w) {
  d: path("M5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gz0-0ft4b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 7a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.kj672_yfn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lbllh8b8w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
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

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>

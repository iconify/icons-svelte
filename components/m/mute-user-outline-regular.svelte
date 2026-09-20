<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q8-0ejn0y"/><path class="f69zonn4h"/><path class="m15ww7bpj"/><path class="mx7ei53xw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mute-user-outline-regular" {...props}></Icon>
<style>
:global(.f69zonn4h) {
  d: path("M4 17a4 4 0 0 1 8 0");
}

:global(.m15ww7bpj) {
  d: path("M15 12c2.5 0 4 1 4 3s-1.5 3 -4 3Z");
}

:global(.mx7ei53xw) {
  d: path("m14 19 7 -7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q8-0ejn0y) {
  d: path("M5 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

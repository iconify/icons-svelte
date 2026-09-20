<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="dy9tza2iq"/><path class="k7qu5ueqh"/><path class="c9ga8t7-s"/><path class="f-5fmfwpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:judge-rubric-outline-regular" {...props}></Icon>
<style>
:global(.c9ga8t7-s) {
  d: path("M11 11.5a2 2 0 0 1 -4 0");
}

:global(.dx3ubrb9h) {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.dy9tza2iq) {
  d: path("M8 10.5h8");
}

:global(.f-5fmfwpk) {
  d: path("M17 11.5a2 2 0 0 1 -4 0");
}

:global(.hbtmd5b0k) {
  d: path("M9.5 7V2.5h5V7");
}

:global(.k7qu5ueqh) {
  d: path("M12 12v4.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

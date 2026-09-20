<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uih_zvhtv"/><path class="xogm81bqq"/><path class="pfpu_3ppl"/><path class="zjf1fhb5j"/><path class="adb8tobrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bunsen-burner-outline-regular" {...props}></Icon>
<style>
:global(.adb8tobrr) {
  d: path("M12 3c1 2.5 3 3.5 3 5a3 3 0 1 1 -6 0c0 -2 1.5 -2.5 1.5 -3.5 0.5 1 1.5 1 1.5 -1.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.xogm81bqq) {
  d: path("M10 21v-9h4v9");
}

:global(.zjf1fhb5j) {
  d: path("M14 17h5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lzbti609i"/><path class="q3srlnbfr"/><path class="z55i2tbmp"/><path class="mb7g-z76v"/><path class="avnm-g99q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-poisoning-outline-bold" {...props}></Icon>
<style>
:global(.avnm-g99q) {
  d: path("m14 12 -4 4");
}

:global(.lzbti609i) {
  d: path("M14 8h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-6l3 -3h3");
}

:global(.mb7g-z76v) {
  d: path("m10 12 4 4");
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z55i2tbmp) {
  d: path("m9 4 3 3 3 -3");
}

</style>

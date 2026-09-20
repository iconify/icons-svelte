<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cqnexabvb"/><path class="ea3ekee5h"/><path class="o-lyxcngp"/><path class="s6wepcb6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compensate-outline-regular" {...props}></Icon>
<style>
:global(.cqnexabvb) {
  d: path("M4 8h13");
}

:global(.ea3ekee5h) {
  d: path("M17 5.5 19.5 8 17 10.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-lyxcngp) {
  d: path("M7 16h13");
}

:global(.s6wepcb6n) {
  d: path("M7 13.5 4.5 16 7 18.5");
}

</style>

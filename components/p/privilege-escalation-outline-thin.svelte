<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0z9iab1m"/><path class="e2nq-yvbg"/><path class="xidycypec"/><path class="drjiz3bcf"/><path class="p75nrtb_v"/><path class="onqwyfb2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:privilege-escalation-outline-thin" {...props}></Icon>
<style>
:global(.a0z9iab1m) {
  d: path("M14 2h2.5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3h-9a3 3 0 0 1 -3 -3V5a3 3 0 0 1 3 -3H10");
}

:global(.drjiz3bcf) {
  d: path("M12 21h2.5");
}

:global(.e2nq-yvbg) {
  d: path("M12 15v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.onqwyfb2z) {
  d: path("M10.5 6h4v4");
}

:global(.p75nrtb_v) {
  d: path("m9.5 11 5 -5");
}

:global(.xidycypec) {
  d: path("M12 18h3");
}

</style>

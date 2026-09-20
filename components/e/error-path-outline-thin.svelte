<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akm88w1ho"/><path class="v_3erbqcl"/><path class="c05571vet"/><path class="puhwuz9ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:error-path-outline-thin" {...props}></Icon>
<style>
:global(.akm88w1ho) {
  d: path("M2 8h7l4 4h9");
}

:global(.c05571vet) {
  d: path("m16 15 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.puhwuz9ig) {
  d: path("m20 15 -4 4");
}

:global(.v_3erbqcl) {
  d: path("m9 8 4 -4h9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g3lrzsbos"/><path class="z_7v15bik"/><path class="cabegubdh"/><path class="ub1mcfbjy"/><path class="xpjur0b_h"/><path class="p0hi_9aen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-merge-outline-regular" {...props}></Icon>
<style>
:global(.cabegubdh) {
  d: path("M14 5h7");
}

:global(.g3lrzsbos) {
  d: path("M3 5h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p0hi_9aen) {
  d: path("M5 17h14");
}

:global(.ub1mcfbjy) {
  d: path("M14 9h7");
}

:global(.xpjur0b_h) {
  d: path("M12 11.5V14");
}

:global(.z_7v15bik) {
  d: path("M3 9h7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sk9l6wbqr"/><path class="y1fcedezv"/><path class="xppaj6pdf"/><path class="fte_yhqex"/><path class="st0l3zbpw"/><path class="dbly1fcej"/><path class="g3lrzsbos"/><path class="z_7v15bik"/><path class="cabegubdh"/><path class="ub1mcfbjy"/><path class="xpjur0b_h"/><path class="p0hi_9aen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-merge-duotone-regular" {...props}></Icon>
<style>
:global(.cabegubdh) {
  d: path("M14 5h7");
}

:global(.dbly1fcej) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 17h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fte_yhqex) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.sk9l6wbqr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.st0l3zbpw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ub1mcfbjy) {
  d: path("M14 9h7");
}

:global(.xpjur0b_h) {
  d: path("M12 11.5V14");
}

:global(.xppaj6pdf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1fcedezv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_7v15bik) {
  d: path("M3 9h7");
}

</style>

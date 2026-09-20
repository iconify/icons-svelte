<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y8z_ge47r"/><path class="sg3hqpbqs"/><path class="usloc3bfa"/><path class="ns4vl7b2c"/><path class="whe30x01i"/><path class="l7_n0rkwd"/><path class="a9dl0vblp"/><path class="k6x6uv-ap"/><path class="s9l3g3b4l"/><path class="du_3_4tit"/><path class="u8rhnqeij"/><path class="dt6efbtua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logit-bias-duotone-regular" {...props}></Icon>
<style>
:global(.a9dl0vblp) {
  d: path("M6 6v13");
}

:global(.dt6efbtua) {
  d: path("M9.5 6 12 8.5 14.5 6");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.k6x6uv-ap) {
  d: path("M12 11v8");
}

:global(.l7_n0rkwd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 6 12 8.5 14.5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ns4vl7b2c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 21.5h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s9l3g3b4l) {
  d: path("M18 6v13");
}

:global(.sg3hqpbqs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u8rhnqeij) {
  d: path("M12 2.5V5");
}

:global(.usloc3bfa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.whe30x01i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 2.5V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y8z_ge47r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 6v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

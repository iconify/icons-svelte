<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="kb-l2shgb"/><path class="ngq__vbsk"/><path class="t1vqlex4a"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="rjyodzkad"/><path class="a9txaac_h"/><path class="j4d2337wb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:http-put-duotone-regular" {...props}></Icon>
<style>
:global(.a9txaac_h) {
  d: path("M12 10.5V16");
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.j4d2337wb) {
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
}

:global(.kb-l2shgb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 7.5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ku_telleq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.ngq__vbsk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 10.5V16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjyodzkad) {
  d: path("M9.5 7.5h5");
}

:global(.t1vqlex4a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 13 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wywiukbgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

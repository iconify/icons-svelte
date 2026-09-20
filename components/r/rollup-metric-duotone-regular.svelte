<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="lt5o_jbwp"/><path class="tonojwfes"/><path class="b5dtkqn-k"/><path class="sgd11y54u"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4gh801hs"/><path class="qui36tb8q"/><path class="ygselab1a"/><path class="plvacbczu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollup-metric-duotone-regular" {...props}></Icon>
<style>
:global(.b5dtkqn-k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lt5o_jbwp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.p4gh801hs) {
  d: path("M8 14v4");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.plvacbczu) {
  d: path("M18 7v11");
}

:global(.qui36tb8q) {
  d: path("M11 12v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sgd11y54u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tonojwfes) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ygselab1a) {
  d: path("M14 15v3");
}

</style>

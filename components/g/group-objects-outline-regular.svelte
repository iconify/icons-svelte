<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hj9iwxbta"/><path class="jw66ugylr"/><path class="wicabhb9r"/><path class="jxp75v9zz"/><path class="isc2z9v1t"/><path class="djp_plbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:group-objects-outline-regular" {...props}></Icon>
<style>
:global(.djp_plbvm) {
  d: path("M19.5 22H22v-2.5");
}

:global(.hj9iwxbta) {
  d: path("M2 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.isc2z9v1t) {
  d: path("M2 19.5V22h2.5");
}

:global(.jw66ugylr) {
  d: path("M14 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.jxp75v9zz) {
  d: path("M19.5 2H22v2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wicabhb9r) {
  d: path("M2 4.5V2h2.5");
}

</style>

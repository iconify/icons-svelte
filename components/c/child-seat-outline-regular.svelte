<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dhw73cmjs"/><path class="phi1ncbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:child-seat-outline-regular" {...props}></Icon>
<style>
:global(.dhw73cmjs) {
  d: path("M6 21V6l3 -3h7v12h3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.phi1ncbih) {
  d: path("M6 15h10");
}

</style>

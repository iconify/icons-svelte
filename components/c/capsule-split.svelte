<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gonsmsbdc"/><path class="p4i731bfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capsule-split" {...props}></Icon>
<style>
:global(.gonsmsbdc) {
  fill: currentColor;
  d: path("m9.75 9.75l-5 5a3.25 3.25 0 0 0 4.5 4.5l5-5Z");
}

:global(.p4i731bfw) {
  d: path("m9.75 9.75l5-5a3.25 3.25 0 0 1 4.5 4.5l-5 5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGjB6XycJA"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="ivjvz2eii"><path class="xxiie10rz"/><circle class="qufharbmm"/><circle class="p9rvr-ggk"/></g></mask></defs><circle mask="url(#SVGjB6XycJA)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:division-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ivjvz2eii) {
  fill: var(--svg-color--000, #000);
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.p9rvr-ggk) {
  cx: 10px;
  cy: 14.5px;
  r: 1.5px;
}

:global(.qufharbmm) {
  cx: 10px;
  cy: 5.5px;
  r: 1.5px;
}

:global(.xxiie10rz) {
  d: path("M5 11a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

</style>

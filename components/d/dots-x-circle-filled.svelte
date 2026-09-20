<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGask04d0u"><path class="k5-vjlrin"/><g transform="translate(3 3)" class="ivjvz2eii"><circle class="zm0the13b"/><circle class="ehbqml5ic"/><circle class="z4qfeoj9o"/></g></mask></defs><circle mask="url(#SVGask04d0u)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:dots-x-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.ehbqml5ic) {
  cx: 10px;
  cy: 10px;
  r: 2px;
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

:global(.z4qfeoj9o) {
  cx: 15px;
  cy: 10px;
  r: 2px;
}

:global(.zm0the13b) {
  cx: 5px;
  cy: 10px;
  r: 2px;
}

</style>

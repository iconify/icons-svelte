<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGCRXgJdzz"><path class="k5-vjlrin"/><path class="zfzpe32mj"/></mask></defs><circle mask="url(#SVGCRXgJdzz)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:play-circle-filled" {...props}></Icon>
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

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

:global(.zfzpe32mj) {
  fill: var(--svg-color--000, #000);
  d: path("M18.544 12.59a1 1 0 0 1-.053 1.728L9.476 19.2A1 1 0 0 1 8 18.321V7.804a1 1 0 0 1 1.53-.848z");
}

</style>

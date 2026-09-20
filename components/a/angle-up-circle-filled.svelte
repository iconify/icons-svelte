<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGZw9zTozP"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path class="ym3qiobuf"/><path class="m9i11s9ez"/></g></mask></defs><circle mask="url(#SVGZw9zTozP)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:angle-up-circle-filled" {...props}></Icon>
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

:global(.m9i11s9ez) {
  d: path("m6.36 14.732l6-5c1.024-.854 2.305.683 1.28 1.536l-6 5c-1.024.854-2.305-.683-1.28-1.536");
}

:global(.ym3qiobuf) {
  d: path("m18.36 16.268l-6-5c-1.025-.853.256-2.39 1.28-1.536l6 5c1.024.853-.256 2.39-1.28 1.536");
}

</style>

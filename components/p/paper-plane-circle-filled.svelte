<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGVOkdCchU"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="a8ml5mr4q"/><path class="lpqbqkp2k"/></g></mask></defs><circle mask="url(#SVGVOkdCchU)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:paper-plane-circle-filled" {...props}></Icon>
<style>
:global(.a8ml5mr4q) {
  fill-rule: evenodd;
  d: path("M4.685 9.659c-.926.309-.906 1.626.03 1.906l7.493 2.242l2.447 7.71c.293.922 1.596.932 1.902.013L21.86 5.62a1 1 0 0 0-1.265-1.265zm3.633.897l11.012-3.67l-3.698 11.096l-1.677-5.284a1 1 0 0 0-.667-.655z");
}

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

:global(.lpqbqkp2k) {
  d: path("m20.767 4.44l1.044 1.077l-8.828 8.543l-1.044-1.077z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGMxxGUObC"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="e6_rmso3h"/></mask></defs><circle mask="url(#SVGMxxGUObC)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:bank-circle-filled" {...props}></Icon>
<style>
:global(.bd9gczbnq) {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

:global(.e6_rmso3h) {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M13 6.864L10.402 8.5h5.196zm.267-2.196a.5.5 0 0 0-.533 0L4.939 9.577c-.424.267-.235.923.267.923h15.588c.502 0 .691-.656.267-.923zM4.5 20a1 1 0 0 1 1-1h15a1 1 0 1 1 0 2h-15a1 1 0 0 1-1-1M7 11.5a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1m3 0a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1m3 0a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1m3 0a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1m3 0a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.k5-vjlrin) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

</style>

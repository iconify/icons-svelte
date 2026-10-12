<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z4gt_lbyk"/><path class="qtprv0uao"/><path class="vbjqiccip"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fingerprint-check-sharp" {...props}></Icon>
<style>
:global(.qtprv0uao) {
  d: path("M8.75 20.25L8 18.225V14a4 4 0 0 1 8 0v3.571L15.5 19");
}

:global(.vbjqiccip) {
  d: path("M12 14v4.629l1.1 2.121");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z4gt_lbyk) {
  d: path("M6 5.75a10.2 10.2 0 0 1 12 0M5 17.25c-.15-.75-.25-1.5-.25-2.25v-1a7.25 7.25 0 0 1 14.5 0v3.225l-.6 2.025");
}

</style>

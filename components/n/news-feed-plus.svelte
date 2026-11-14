<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d7o2ez0pg"/><path class="phb_cwxlg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:news-feed-plus" {...props}></Icon>
<style>
:global(.d7o2ez0pg) {
  d: path("M12.2 20.5H2.5v-18h18v9.7M6 6.5h11");
}

:global(.phb_cwxlg) {
  d: path("M6 9.75h5.5v5.5H6Zm8.25.5H17M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

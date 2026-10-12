<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="lcyinnbmm"/><circle class="u_qlszbyq"/><circle class="idf1-xb5a"/><circle class="m8k5k22cc"/><circle class="mscsd_b2w"/><circle class="zopjch_2q"/><path class="bhasjyqja"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grapes-sharp" {...props}></Icon>
<style>
:global(.bhasjyqja) {
  d: path("M12 5.5V2.75h2.5");
}

:global(.idf1-xb5a) {
  cx: 18.5px;
  cy: 7.5px;
  r: 2px;
}

:global(.lcyinnbmm) {
  cx: 5.5px;
  cy: 7.5px;
  r: 2px;
}

:global(.m8k5k22cc) {
  cx: 8.75px;
  cy: 13.25px;
  r: 2px;
}

:global(.mscsd_b2w) {
  cx: 15.25px;
  cy: 13.25px;
  r: 2px;
}

:global(.u_qlszbyq) {
  cx: 12px;
  cy: 7.5px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zopjch_2q) {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>

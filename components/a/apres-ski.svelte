<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dcpcchr6g"/><path class="sr2dxpbpd"/><path class="sgu1u_bco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:apres-ski" {...props}></Icon>
<style>
:global(.dcpcchr6g) {
  d: path("m5.507 9.668l5.447.766l-1.461 10.398l-5.447-.766Z");
}

:global(.sgu1u_bco) {
  d: path("m18.806 11.896l2.228-.313l.661 4.704l-2.228.313M7.5 7.5c-1-1.25 1-2.5 0-4m9 4c1-1.25-1-2.5 0-4");
}

:global(.sr2dxpbpd) {
  d: path("m5.194 11.896l-2.228-.313l-.661 4.704l2.228.313m8.513-6.166l5.447-.766l1.461 10.398l-5.447.766Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

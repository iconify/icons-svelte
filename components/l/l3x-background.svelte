<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="djpqckb1v"/><path class="vhyl095-s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:l3x-background" {...props}></Icon>
<style>
:global(.djpqckb1v) {
  fill: var(--svg-color--48ea98, #48ea98);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.vhyl095-s) {
  fill: var(--svg-color--000, #000);
  d: path("M17.6 15.919v-.325h-4.094v.51l-.001.033q-.015.207-.225.221l-.033.001H6.4v2.25L8.235 20h5.317q4.002-.045 4.047-3.99zm-9.495-2.644v-3.014h9.412v3.014zM13.551 4H8.47L6.635 5.391v2.25h6.645q.118.009.175.078a.25.25 0 0 1 .05.144v.543H17.6v-.417Q17.552 4.044 13.55 4");
}

</style>

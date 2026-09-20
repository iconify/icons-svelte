<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="nxeaqlb0c"/><path class="q4rqiabhv"/><path class="i0w_lcl8b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:dseth-background" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i0w_lcl8b) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 9.474v5.052l4.63-2.947z");
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.nxeaqlb0c) {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.895 16.05l-4.63-2.786L9.894 20zm4.21 0l4.63-2.786L14.106 20zM12 9.684V4l-4.63 7.578z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.q4rqiabhv) {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 9.473v5.052l-4.63-2.947zm0 .21V4l4.632 7.578z");
}

</style>

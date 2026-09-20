<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="s5mls-hjo"/><path class="grcmukbty"/><path class="mmfyo5b-e"/><path class="vrzoejbxi"/><path class="qphf_rk4u"/><path class="qjkpuomzo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:foom-background" {...props}></Icon>
<style>
:global(.beaf9ac8r) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.grcmukbty) {
  fill: var(--svg-color--00f8ff, #00f8ff);
  d: path("M4 6.5h14v13H4z");
}

:global(.mmfyo5b-e) {
  fill: var(--svg-color--000, #000);
  d: path("M5 5.502h14v13H5z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.qjkpuomzo) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 9.5h6l-.55.75H10.5v1.25h4.325l-.66.75H10.5v2.25H9z");
}

:global(.qphf_rk4u) {
  fill: var(--svg-color--red, red);
  d: path("M9.5 9.002h6l-.55.75H11v1.25h4.326l-.66.75H11v2.25H9.5z");
}

:global(.s5mls-hjo) {
  fill: var(--svg-color--red, red);
  d: path("M6.5 4.5H20V18H6.5z");
}

:global(.vrzoejbxi) {
  fill: var(--svg-color--00f8ff, #00f8ff);
  d: path("M8.5 10h6l-.55.75H10V12h4.326l-.66.75H10V15H8.5z");
}

</style>

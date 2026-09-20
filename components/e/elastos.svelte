<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="g9efgbbhd"><path class="fok83nbnk"/><path class="yv9ht-7ex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:elastos" {...props}></Icon>
<style>
:global(.fok83nbnk) {
  d: path("m12 12.31l4.5-2.5L21 7.299L16.5 4.8L12 7.298L7.5 4.8L3 7.298L7.5 9.81z");
}

:global(.g9efgbbhd) {
  fill: var(--svg-color--8530f1, #8530f1);
}

:global(.yv9ht-7ex) {
  d: path("M16.5 11.692L12 14.189l-4.5-2.498L3 14.19l4.5 2.513L12 19.2l4.5-2.498L21 14.19z");
}

</style>

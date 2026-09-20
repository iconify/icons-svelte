<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="sv0voacfr"/><path class="r1979lb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:anchor" {...props}></Icon>
<style>
:global(.r1979lb7o) {
  fill: var(--svg-color--269, #269);
  d: path("M18 0a6 6 0 1 0 0 12a6 6 0 0 0 0-12m0 9a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

:global(.sv0voacfr) {
  fill: var(--svg-color--269, #269);
  d: path("M30.5 18.572L26 25h2.575A11 11 0 0 1 20 32.81V17h3a2 2 0 0 0 0-4h-3v-1.349h-4V13h-3a2 2 0 0 0 0 4h3v15.81A11 11 0 0 1 7.425 25H10l-4.5-6.428L1 25h3.33C5.705 31.289 11.299 36 18 36s12.295-4.711 13.67-11H35z");
}

</style>

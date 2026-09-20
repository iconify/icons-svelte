<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="fh_1d4_pj"/><path class="fbdudye6k"/><path class="ss5n3z8ni"/><path class="seyfi9bwj"/><path class="rby8lzb1r"/><path class="jfrj8mp_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-wallis-and-futuna" {...props}></Icon>
<style>
:global(.fbdudye6k) {
  fill: var(--svg-color--eee, #EEE);
  d: path("M0 16h19v2H0z");
}

:global(.fh_1d4_pj) {
  fill: var(--svg-color--ed2939, #ED2939);
  d: path("M32 5H18v12H0v10a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

:global(.jfrj8mp_t) {
  d: path("M24.38 22.32h6.24L27.5 19.2zM30.62 14h-6.24l3.12 3.12zm1.04 7.28v-6.24l-3.12 3.12zm-8.32-6.24v6.24l3.12-3.12z");
  fill: var(--svg-color--fff, #FFF);
}

:global(.rby8lzb1r) {
  fill: var(--svg-color--ed2939, #ED2939);
  d: path("M12 5h6v12h-6z");
}

:global(.seyfi9bwj) {
  fill: var(--svg-color--eee, #EEE);
  d: path("M6 5h6v12H6zm11 0h2v13h-2z");
}

:global(.ss5n3z8ni) {
  fill: var(--svg-color--002395, #002395);
  d: path("M6 17H0V9a4 4 0 0 1 4-4h2v12z");
}

</style>

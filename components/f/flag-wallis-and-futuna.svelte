<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ldigwccbs"/><path class="ox-xtt67x"/><path class="iq17nab3k"/><path class="pm_yxygqs"/><path class="v3e472byx"/><path class="mgk62cc3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-wallis-and-futuna" {...props}></Icon>
<style>
:global(.iq17nab3k) {
  fill: var(--svg-color--002395, #002395);
  d: path("M6 17H0V9a4 4 0 0 1 4-4h2z");
}

:global(.ldigwccbs) {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M32 5H18v12H0v10a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

:global(.mgk62cc3l) {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.38 22.32h6.24L27.5 19.2zM30.62 14h-6.24l3.12 3.12zm1.04 7.28v-6.24l-3.12 3.12zm-8.32-6.24v6.24l3.12-3.12z");
}

:global(.ox-xtt67x) {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 16h19v2H0z");
}

:global(.pm_yxygqs) {
  fill: var(--svg-color--eee, #eee);
  d: path("M6 5h6v12H6zm11 0h2v13h-2z");
}

:global(.v3e472byx) {
  fill: var(--svg-color--ed2939, #ed2939);
  d: path("M12 5h6v12h-6z");
}

</style>

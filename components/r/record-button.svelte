<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y_aqcmi-i"/><circle class="tcgfi6b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:record-button" {...props}></Icon>
<style>
:global(.tcgfi6b_o) {
  cx: 64px;
  cy: 64px;
  r: 32px;
  fill: var(--svg-color--40c0e7, #40c0e7);
}

:global(.y_aqcmi-i) {
  fill: none;
  d: path("M128 128H0V0h128z");
}

</style>

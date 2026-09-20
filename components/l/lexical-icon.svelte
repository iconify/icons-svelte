<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":243};
const content = `<path class="ugggrvbpi"/><path class="g8u66cbvc"/><path class="n4qfu3b1j"/><path class="urd8rjbti"/><path class="fl4b_1b4b"/><path class="i3nxq9b4d"/><path class="fd4no41bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:lexical-icon" {...props}></Icon>
<style>
:global(.fd4no41bd) {
  d: path("M236.475 0v21.695H212.61v199.593h23.865v21.695H169.22v-21.695h21.695V21.695H169.22V0zm-56.407 32.542v21.695H21.695v134.509h158.373v21.695H0V32.542zm75.932 0v177.899h-32.542v-21.695h10.847V54.237h-10.847V32.542z");
}

:global(.fl4b_1b4b) {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M101.966 145.356h47.729v21.695h-47.729z");
}

:global(.g8u66cbvc) {
  d: path("M101.966 75.932h47.729v21.695h-47.729z");
}

:global(.i3nxq9b4d) {
  d: path("M160.542 145.356h19.526v21.695h-19.526z");
}

:global(.n4qfu3b1j) {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M160.542 75.932h19.526v21.695h-19.526zM43.39 110.644h78.102v21.695H43.39zm88.949 0h47.729v21.695h-47.729z");
}

:global(.ugggrvbpi) {
  fill: var(--svg-color--76b6ff, #76b6ff);
  d: path("M43.39 75.932h47.729v21.695H43.39z");
}

:global(.urd8rjbti) {
  d: path("M43.39 145.356h47.729v21.695H43.39z");
}

</style>

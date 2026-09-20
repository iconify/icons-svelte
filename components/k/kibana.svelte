<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":328};
const content = `<path class="vwuoxgbdy"/><path class="gr07_3bcm"/><path class="jbcvi5biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:kibana" {...props}></Icon>
<style>
:global(.gr07_3bcm) {
  fill: var(--svg-color--343741, #343741);
  d: path("M0 122.88v171.91l122.194-140.71C85.862 134.277 44.288 122.88 0 122.88");
}

:global(.jbcvi5biz) {
  fill: var(--svg-color--00bfb3, #00bfb3);
  d: path("M148.59 170.54L23.2 314.945l-11.069 12.738h238.736C237.77 263.13 200.302 207.496 148.59 170.54");
}

:global(.vwuoxgbdy) {
  fill: var(--svg-color--f04e98, #f04e98);
  d: path("M256 0H0v294.789z");
}

</style>

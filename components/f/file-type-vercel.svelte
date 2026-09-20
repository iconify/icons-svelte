<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGhEEgheoe" x1="1.459" x2="1.096" y1="32.377" y2="32.82" gradientTransform="matrix(113 0 0 -100 -112 3301)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><path fill="url(#SVGhEEgheoe)" class="cenkntzcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-vercel" {...props}></Icon>
<style>
:global(.cenkntzcp) {
  fill-rule: evenodd;
  d: path("m16 3.611l14 24.778H2z");
}

:global(.vc--wpv5i) {
  stop-color: var(--svg-color--fff, #fff);
}

</style>

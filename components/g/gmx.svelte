<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGUNUwVcIq)" class="tk1eg-b3a"/><defs><linearGradient id="SVGUNUwVcIq" x1="12.65" x2="6.375" y1="5.365" y2="20.33" gradientUnits="userSpaceOnUse"><stop class="u315cdrqy"/><stop offset="1" class="hrq8_nbkj"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:gmx" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hrq8_nbkj) {
  stop-color: var(--svg-color--4e09f8, #4e09f8);
}

:global(.tk1eg-b3a) {
  d: path("M21 19L12.015 5L3 19h12.56l-3.55-5.345l-1.75 2.845H8.385l3.63-5.65L17.26 19z");
}

:global(.u315cdrqy) {
  stop-color: var(--svg-color--03d1cf, #03d1cf);
  stop-opacity: 0.99;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="u2bgohdzx"/><path class="cugumcbbj"/><path class="qmsms8bjm"/><path class="dzimeordr"/><path class="s1y-dje8y"/><path class="mzdmjcc3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:house-broken" {...props}></Icon>
<style>
:global(.cugumcbbj) {
  d: path("M15.5 5.5V3.5C15.5 3.22386 15.7239 3 16 3H18.5C18.7761 3 19 3.22386 19 3.5V8.5");
}

:global(.dzimeordr) {
  d: path("M20 17.5V22M20 9.5V13.5");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzdmjcc3w) {
  d: path("M14 9.5C14 10.6046 13.1046 11.5 12 11.5C10.8954 11.5 10 10.6046 10 9.5C10 8.39543 10.8954 7.5 12 7.5C13.1046 7.5 14 8.39543 14 9.5Z");
}

:global(.qmsms8bjm) {
  d: path("M4 22V9.5");
}

:global(.s1y-dje8y) {
  stroke-linejoin: round;
  d: path("M15 22V17C15 15.5858 15 14.8787 14.5607 14.4393C14.1213 14 13.4142 14 12 14C10.5858 14 9.87868 14 9.43934 14.4393M9 22V17");
}

:global(.u2bgohdzx) {
  d: path("M22 11L13.8741 4.49928C12.7784 3.62276 11.2216 3.62276 10.1259 4.49928L9.34398 5.12483M2 11L6.06296 7.74965");
}

:global(.xpzbxokqs) {
  d: path("M22 22L2 22");
}

</style>

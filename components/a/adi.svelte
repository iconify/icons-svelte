<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJfDAH9lU)" class="se2nd1xwj"/><defs><linearGradient id="SVGJfDAH9lU" x1="12" x2="12" y1="9.975" y2="18.079" gradientUnits="userSpaceOnUse"><stop class="jpp7j9b0m"/><stop offset="1" class="uoxpj2blc"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:adi" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jpp7j9b0m) {
  stop-color: var(--svg-color--fe7109, #fe7109);
}

:global(.se2nd1xwj) {
  d: path("M17.548 11.821a.34.34 0 0 1 0 .357l-5.252 8.656a.346.346 0 0 1-.592 0l-5.253-8.655a.34.34 0 0 1 0-.357l5.253-8.656a.346.346 0 0 1 .591 0zm-8.627-.346c-.14.23.026.523.296.523h5.567a.344.344 0 0 0 .295-.523L12.296 6.89a.346.346 0 0 0-.592 0zM12 9.048a.98.98 0 1 1 .001 1.96a.98.98 0 0 1-.001-1.96");
}

:global(.uoxpj2blc) {
  stop-color: var(--svg-color--003bff, #003bff);
}

</style>
